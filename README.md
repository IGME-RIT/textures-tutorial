# Textures Tutorial

This program demonstrates an implementation for loading a PNG texture.

# About

Introduces the idea of texturing by loading a PNG texture with SOIL. The texture is then passed into glTexImage2D to create a 2D texture. In this example, we use glBlendFunc to control the alpha blending, since the PNG file has transparency. Each vertex passed into the Vertex Shader will have UV texture coordinates as well. These are passed through to the Fragment Shader, where they are used as the 2D index to sample color from the texture.

# Setup

In order to setup, run the following in a shell, then open the project in your preferred editor. Windows setup has been configured for use with Visual Studio.

Windows:
```
cd path/to/folder
setup.cmd
```
Linux:
```
cd path/to/folder
./setup
```
