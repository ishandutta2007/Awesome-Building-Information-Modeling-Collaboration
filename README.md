# Awesome-Building-Information-Modeling-Collaboration

# Awesome-Building-Information-Modeling-Collaboration

## Top Building Information Modeling (BIM) Collaboration Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Model Coordination, Issue Tracking & Common Data Environments*  

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **BIM Collaboration**. These tools enable architecture, engineering, and construction (AEC) teams to share models, coordinate disciplines, manage issues, and maintain a Common Data Environment (CDE) throughout the project lifecycle.



**Examples** include Autodesk BIM Collaborate, Revizto, Trimble Connect, Dalux, BIM Track, Catenda, BIM 360, Bricsys 24/7, Newforma, and Solibri Office (the category leaders).



**Open-source emphasis**: This section is expanded with active projects for self-hosting, custom CDE workflows, and transparent model data — ideal for AEC firms, developers, and researchers building vendor-independent BIM collaboration solutions. The open-source ecosystem offers strong foundations for model viewing, server-based data management, and real-time collaboration.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Autodesk BIM Collaborate](https://www.autodesk.com/)**  

  Cloud-based design collaboration and model coordination platform integrated with Autodesk Construction Cloud. Includes model aggregation, clash detection, and issue management .



- **[Revizto](https://revizto.com/)**  

  Issue-centric coordination platform with 2D/3D review, clash collaboration, and mobile field review. Estimated 180k users with strong presence in contractor and VDC workflows .



- **[Trimble Connect](https://connect.trimble.com/)**  

  Project information management and CDE platform connecting design, build, and operate phases across Trimble's construction ecosystem .



- **[Dalux](https://www.dalux.com/)**  

  CDE and field management platform known for strong mobile BIM viewer and QR-code-based plan verification on site .



- **[BIM Track](https://www.bimtrack.co/)**  

  Issue and BCF coordination platform with clash workflow and multi-tool collaboration. Estimated 65k users focused on coordination teams and design managers .



- **[Catenda](https://catenda.com/)**  

  OpenBIM-based CDE platform supporting IFC and BCF standards for collaborative model management.



- **[BIM 360](https://www.autodesk.com/)**  

  Autodesk's legacy cloud platform for construction management, now part of Autodesk Construction Cloud .



- **[Bricsys 24/7](https://www.bricsys.com/)**  

  Cloud-based document and project collaboration platform with BIM viewing capabilities.



- **[Newforma](https://www.newforma.com/)**  

  Project information management software for AEC firms, focused on email, file, and RFI management.



- **[Solibri Office](https://www.solibri.com/)**  

  Model checking and quality assurance platform for BIM, with rule-based validation and coordination tools.



## Open-Source GitHub Projects



- **[BIMserver](https://github.com/opensourceBIM/BIMserver)**  

  The original open-source BIM server platform with 800+ GitHub stars, enabling storage and management of construction project data using the open IFC data standard. Model-driven architecture stores IFC data as objects (not files), functioning as an IFC database with versioning, merging, model checking, and multi-user support. Users work on their own data parts while the complete dataset updates on the fly, with notifications for model updates. AGPL-3.0 licensed with active development as of March 2026. buildingSMART certified for IFC 2x3 full and IFC 4 full compliance .



- **[Speckle](https://github.com/specklesystems/speckle-server)**  

  Open-source data infrastructure for the AEC industry with 1,200+ stars, described as "Git & Hub for geometry and BIM data." Object-based platform replacing file-based workflows with a real-time database. Features version control, 3D viewer, GraphQL API, webhooks, and real-time collaboration. Connectors for Revit, Rhino, Grasshopper, AutoCAD, Civil 3D, Excel, Unreal Engine, Unity, QGIS, Blender, ArchiCAD, and Power BI enable interoperability without export/import. Self-hostable via Docker Compose with server, frontend, viewer, and object loader components .



- **[Bldrs Share](https://github.com/bldrs-ai/Share)**  

  Browser-based BIM & CAD viewer and collaboration platform supporting IFC 2x3 & 4, STL, OBJ, and STEP (early access). Features drag-and-drop model viewing with no data upload, offline capability, section planes, property editing, CSV data export, real-time link sharing, multi-user timeline-based versioning in Git, and issue tracking with in-model placemarks. Built on open standards with an extensible Apps framework for Digital Twin lifecycle systems. Supports on-prem/data sovereignty with GitLab (early access) .



- **[xeokit-bim-viewer](https://github.com/xeokit/xeokit-bim-viewer)**  

  Open-source IFC, BIM, and point cloud 3D viewer built with the xeokit SDK. Enables AEC & GIS applications with double precision global coordinates. Supports combined geometry and metadata in XKT files, with backward compatibility for older XKT+JSON separation. Features split-model loading with manifest.json for multi-part models. BSD-licensed with active development .



- **[ifc-lite](https://github.com/LTplus-AG/ifc-lite)**  

  Rust + WASM core for parsing, viewing, querying, editing, and exporting IFC files in the browser with WebGPU rendering. Works with IFC2X3, IFC4/IFC4X3, and IFC5 (IFCX). Features ~260 KB gzipped bundle, 5x faster geometry processing, columnar parsing, SQL queries via DuckDB-WASM, IDS validation, mutable property views with undo, and export to STEP/Parquet/IFC5. The **collab package** adds real-time collaborative BIM editing via CRDT (Yjs document mirroring IFCX data model), enabling concurrent edits that converge without central locks, online or offline. Supports presence (live cursors/selections), conflict detection, and user-layer extraction. Reference websocket sync server with file/Redis/S3 persistence backends and secure server bundle with TLS, JWT auth, and rate limiting .



- **[ConvergeStudio](https://github.com/wieslawsoltes/ConvergeStudio)**  

  Open-source BIM coordination and clash detection tool with browser-based interface. Features model tree navigation, property inspection, section planes, and clash detection with 1 micrometre numerical epsilon. Supports IFC (native reader and optional web-ifc WASM adapter) and glTF 2.0/GLB with hierarchy, node transforms, and metadata. Architecture uses native JavaScript modules with WebGPU/WGSL and WebGL2/GLSL rendering backends, plus a software fallback renderer. Coordination semantics distinguish hard clashes (triangle contact/intersection) from clearance results (nearest surface distance within threshold). Review statuses attach to stable entity-pair IDs with staleness marking after model edits .



- **[Online 3D Viewer](https://github.com/yhzcake/Online3DViewer)**  

  Free and open-source web solution to visualize and explore 3D models in the browser. Supports import of 3dm, 3ds, 3mf, amf, bim, brep, dae, fbx, fcstd, gltf, ifc, iges, step, stl, obj, off, ply, and wrl formats. Export to 3dm, bim, gltf, obj, off, stl, and ply. Built on three.js, web-ifc, occt-import-js, and other libraries. Lightweight viewer suitable for quick model inspection and sharing .



- **[GomeraX](https://github.com/salpbes/GomeraX)**  

  Experimental IFC viewer with local AI assistant. Features WebGL and experimental WebGPU rendering modes, IFC file conversion to Fragments, hierarchical property inspection, Excel-like property tables with filtering/sorting, sectioning with preset planes, measurement tools (length/area/volume), 2D floor plan views, and Level of Detail (LOD) system for massive models with millions of triangles. Automatic model alignment to site coordinates .



### Additional Strong Open-Source Options



- **OpenBIM Collective** — Umbrella organization maintaining BIMserver and related IFC tooling for the openBIM ecosystem .

- **web-ifc** — WebAssembly-based IFC parsing library used by ConvergeStudio, Online 3D Viewer, and other browser-based BIM tools .

- **IFC.js** — Open-source JavaScript library for IFC parsing and viewing in the browser.

- **That Open Company (formerly IFC.js)** — Open-source platform components for BIM web development including Fragments format.



**Frameworks for building custom BIM collaboration solutions**: Combine **BIMserver** for server-side IFC data management with versioning and multi-user support . Use **Speckle** as the data infrastructure layer for object-based model sharing across disciplines and tools . For browser-based viewing and coordination, **Bldrs Share** or **xeokit-bim-viewer** provide production-ready viewers . For real-time collaborative editing, **ifc-lite collab** offers CRDT-based concurrent model editing with presence and conflict resolution . For clash detection, **ConvergeStudio** provides browser-based coordination with configurable epsilon and status tracking . Note that true enterprise CDE platforms with document control, transmittals, and workflow automation remain largely commercial territory; open-source stacks provide strong model server, viewer, and collaboration foundations that require integration for full project information management.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- BIM collaboration tools must comply with project-specific information management standards (ISO 19650, buildingSMART standards) and contractual requirements.

- Self-hosted open-source solutions require proper infrastructure, IFC data management expertise, and ongoing maintenance. Model federation and clash detection accuracy depend on model quality and coordination discipline.

- The open-source ecosystem provides strong model server, viewer, and real-time collaboration foundations, but full enterprise CDE platforms with document control, transmittals, and workflow automation remain primarily commercial offerings.



---



**Made for architects, engineers, contractors, BIM managers, and AEC technologists.**  

Let's make BIM collaboration more open, transparent, and interoperable.
