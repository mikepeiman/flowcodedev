# # FlowCode Development

## Empowering developers with visual thinking

The goal of this project is to provide a tool that allows the use of intuitive visual concept mapping as the primary mode for architecting software. 

Caveat: I'm approaching this from a front-end developer's perspective, where my goal is to produce working products from scratch, using libraries and tools to make development more rapid and robust, eg. component frameworks like Svelte.

My vision for this tool is to marry the domains of formal software architecture, as represented by technical standards like UML, with the intuitive ease of free-form concept mapping, as one might do with pen and paper, or in apps like (long-defunct) Tufts' Vue, or more recently Figma's Figjam, or Excalidraw. 

But traditional diagramming in any domain has, due to the limits of the software ecosystem, produced dead artifacts, unconnected with the content they represent. I identified this frustration and limitation in personal knowledge management long before I even began my journey of learning software development, ten years ago - and this exact frustration was a primary motivator for that decision.

So, what will we have if our diagrams are not dead, unconnected artifacts?

1. Diagrams will be integrally connected (bi-directional changes) to the underlying code - the file contents and folder structure.
2. Diagrams can produce code and modify the filesystem - you can design your app visually and then have it generate the project, including:
   1. project structure in the filesystem
   2. boilerplate code in files/components
   3. installation and integration via config files of libraries and packages
3. Dataflow (any object/variable/source), logic and operations can be created, mapped, and manipulated via the visual interface (which of course includes code editing in-app or via your code editor of choice)
   1. You can drag-and-drop variables into functions and components. You can drop components into other components or pages.
   2. imports, exports, props, state and similar conventions are implemented automatically, as per developer's configuration preferences. In other words, when you rename a component or a variable, it will be automatically renamed across the project (this is already partially implemented in VS Code for example).
