# metaweb-wiki: 

**Note: this is a placeholder documentation site for a presently private repository being prepared for public management. It contains description and detailed source documentation in many sections, especially the section 'various examples from the e2e_spec' (89 end-to-end tests performance source and commentary)**  

* declarative media production and performance system using declarative composition animation and cinematography layering i3d-webGL, i2d-svg, html-css3d-video-audio, and heads-up hideable UI, and interactive cameras 

* Each media change (scene, i3d, i2d, html-css-video, ui, camera shot) represented and executed as an application state change with unique media components URL which compiles template:model tuples into the DOM and runs angular directives for procedural code generation, and integrates with the browser history

* declarative generative metaform-based interactive 3D component actors based on svg-templates, JSON models and angular directives hiding procedural code generation for webgl-three.js scene branches isomorphic to the declared svg-DOM branches

* declarative actions based performance score and interactive vamera and UI shot 'overdub' for live composition

* live injected unit-tests and performance-specific e2e-tests both executed in the live performance system



### partial features list:<br/>

* es6 angularjs framework with application state composed of six independent template:model tuples forming a state-URL, corresponding (left to right) to scene, i3d, i2d, base-html-css-video-audio, ui, and camera-shot (2d-3d) For example: "/a0:/i3d-simple:simple_green/i2d-scene:disks0/base-skycube:test_cube/ui-msgbg:/shot-graft:scope6"

* multi-layer graphics in webgl, svg, html-css3d-video and html-ui

* independent selective changes to any subset of state-URL components - which causes application state change

* responsive scaled vector-space coordinate graphics and html-css mapping to a 100vw x 100vh (100% x 100%) (100 x 100 svg viewBox units) viewport projection region of an infinite volume.

* performance stage-management, animation and virtual cinematography, as well as unit and end-to-end tests, driven by sequences of declarative 'actions' operating on the viewable production system itself

* declarative performance composition and system configuration by a single object in a single unique index.html file per performance

* integration of forward-backward browser history into the application state-URL sequence

* 'overdubbing' of interactive camera (2d 3d) actions and interactive stage UI actions into the current performance actions sequence to build and record more detailed sequences

* camera apparatus with pan-tilt lens located on the surface of a camerasphere used for pitch-yaw-roll rotation examination of its center focus, dolly translations in x, y and z, and zoom in-out. The camerasphere radius and camera field-of-view create a default 100 x 100 projection plane corresponding to the 100vw x 100vh viewport.

* adjustable key-fill-back lighting apparatus attached to the camerasphere so that it follows all camera dollying rotation and zoom. Light properties and location can be dynamically controlled and turned on-off either by action or by heads-up UI. The heads-up UI can also make scene changes, show-hide 3D, 2D, 2d-axes, base-html-css-video,
frames-per-second graphic, scenename, camerasphere wireframe, and the ui itself is reducible to a single radio button in the upper left corner of the viewport

* declarative three.js objects composed bt i3d-svg-template and JSON model, compiled into the DOM by the angular $compile service, with specified angular directives executing procedural code to silently create three.js scene objects in a scenegraph hierarchy isomorphic to the declarative i3d-svg DOM tree  

* declarative svg via angular svg-templates and JSON models and angular i2d-form directive 

* declarative html-css-video via angular html-templates and JSON models and angular directives - in particular enables augmented reality video

* VR-ready both in terms of stereo displays and hand-finger-motion controllers (implementations in progress)



### install:

* clone the repo

* npm install (via package.json for development and server)

* edit index.html 'base href' in head so that coorect html5 URL references can be made<br/>
set href to the location of index.html in the cloned repo. <br/>
for exp: <br/>
```
<base href="/test/angular-es6/meta-y/app/"/> <!-- test is off the $DocumentRoot -->
```


### documentation:

* refer to the Wiki

* refer to or generate docco source-code comments (gulp docco) 


