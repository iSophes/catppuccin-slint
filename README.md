<h3 align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/logos/exports/1544x1544_circle.png" width="100" alt="Logo"/><br/>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
	Catppuccin for <a href="https://slint.dev/">Slint</a>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
</h3>

<p align="center">
	<a href="https://github.com/isophes/catppuccin-slint/stargazers"><img src="https://img.shields.io/github/stars/isophes/catppuccin-slint?colorA=363a4f&colorB=b7bdf8&style=for-the-badge"></a>
	<a href="https://github.com/isophes/catppuccin-slint/issues"><img src="https://img.shields.io/github/issues/isophes/catppuccin-slint?colorA=363a4f&colorB=f5a97f&style=for-the-badge"></a>
	<a href="https://github.com/isophes/catppuccin-slint/contributors"><img src="https://img.shields.io/github/contributors/isophes/catppuccin-slint?colorA=363a4f&colorB=a6da95&style=for-the-badge"></a>
</p>

# Installation

Copy catppuccin.slint into your project.

> [!NOTE]
> Slint does not have an official package manager, therefore this is the best cross-platform solution.

# Example

```slint
import { Catppuccin } from "catppuccin.slint";

export component AppWindow inherits Window {
    width: 1200px;
    height: 600px;

    background: Catppuccin.Mocha.SurfaceZero;
    
    Rectangle {
        width: 50%;
        height: 50%;
        background: Catppuccin.Mocha.Rosewater;
    }
}

```

# Contributing

See ![CONTRIBUTING.md](CONTRIBUTING.md)

# AI Usage

This project has no AI usage.

<p align="center">
	<a href="https://github.com/iSophes/catppuccin-slint/blob/main/LICENSE"><img src="https://img.shields.io/static/v1.svg?style=for-the-badge&label=License&message=MIT&logoColor=d9e0ee&colorA=363a4f&colorB=b7bdf8"/></a>
</p>
