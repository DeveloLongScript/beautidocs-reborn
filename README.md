<h1 align="center">beautidocs-reborn</h1>
<p align="center">A simplistic documentation website built in Next.js and shadcn/ui.</p><br/>

**Table of Contents**:
1. my inspiration to do this project
   1. [backstory](#backstory)
   2. [changes](#changes)
2. [installation](#installation)
3. [additions & changes](#additions--changes)
4. [why beautidocs](#why-beautidocs)

## backstory
Beautidocs was a project that I worked on a couple of years ago. Now my coding skills are a lot better, however the original idea of making a documentation, with simply 4 files, sparked me to go back and do the project again. This is **not** a fork of the project, rather a version that is higher quality.

Yes, it might not be as customizable, however the simplicity of having 4 files, including a settings, markdown and styling, was begging me to come back to this.

## changes
The original documentation was built inside of SvelteKit, however I don't use SvelteKit much anymore, so I'm moving over to Next.js, which will ultimately change the quality of the project. For the UI library, I was using Material UI, a port for Svelte. This time, I'm using shadcn/ui. I think personally it looks alot better than before, which is why ultimately I'm going to move over to shadcn/ui.

## installation
This repository is the visual part. The direct installer is also [open source](https://github.com/DeveloLongScript/bd-docs).<br/>
**To install:** (on any system with Node)<br/>
`npx bd-docs init`
<br/><br/> Just like the original, there are three commands, `bd-docs init`, to create the files, `bd-docs dev` (which used to be `svelte`) and `bd-docs cleanup`.
<br/>However, there is one additional command, `bd-docs build`.
The reason why `bd-docs dev` and `bd-docs build` was created, was to make it easier to deploy and develop, making it clearer with each command. `bd-docs svelte` wasn't very clear.

## additions & changes
 - `bd-docs build`, for deploying
 - automatic creation of a `package.json`
 - sass -> css (however use `--keep-scss` to keep your Sass files if your migrating)
 - built-in TailwindCSS with `--twcss`
 - custom react support with `--use-mdx`
 - switching to shadcn/ui
 - switching to Next.js
 - cleaner and less buggy UI in general
 - more customization and settings
 - table of contents
 - a signifiantly less buggy sidebar
 - subsections
   
## why beautidocs
As said before, if you just want a simple documentation solution, without having to deal with React files and additional things, with just 4 files in one directory, its pretty simple. It might not be the most customizable thing, however new things are added.
