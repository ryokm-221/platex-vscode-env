# Japanese pLaTeX VSCode Env
Easy way to create **Japanese pLaTeX environment** with VSCode and Docker.

## What is good about?
This is a simple repository to create pLaTeX environment (or any LaTeX compiler) into folder.

## Prerequisite
- Use VSCode
  - Apply Remote Development extension to your VSCode
- Already installed Docker Desktop (or any docker environment)
- Have [Docker Hub](https://hub.docker.com/) Account

## How to use
1. Clone into any folder where you want to use pLaTeX
2. Open folder in VSCode
3. Reopen folder in Container (*[see here](https://code.visualstudio.com/docs/remote/containers) for official support*)
   - **Attention!** Because TexLive docker image is large (approx. 2GB), be careful of network usage when build container image.
4. Since the extensions and settings are already in set, you can build and preview your tex files right now!
   - To build, press green triangle on the top right of tex file tab.

## Thanks
This repository uses following images/extension:
- [texlive/texlive](https://hub.docker.com/r/texlive/texlive) (Docker Image): MIT License
- [LaTeX-Workshop](https://github.com/James-Yu/LaTeX-Workshop) (VSCode Extension): MIT License