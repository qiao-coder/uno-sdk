# unofficial-opengl-SDK

[![Build Status](https://travis-ci.org/kotlin-graphics/uno-sdk.svg?branch=master)](https://travis-ci.org/kotlin-graphics/uno-sdk) 
[![license](https://img.shields.io/badge/License-MIT-orange.svg)](https://github.com/kotlin-graphics/uno-sdk/blob/master/LICENSE) 
![](https://reposs.herokuapp.com/?path=kotlin-graphics/uno-sdk&color=yellow) 
[![Release](https://jitpack.io/v/kotlin-graphics/uno-sdk.svg)](https://jitpack.io/#kotlin-graphics/uno-sdk) 
[![Slack Status](http://slack.kotlinlang.org/badge.svg)](http://slack.kotlinlang.org/)

Modules:

- glfw wrapper
- GlfwWindow

Don't hesitate to contribute to the project by submitting [issues](https://github.com/kotlin-graphics/uno-sdk/issues) or [pull requests](https://github.com/kotlin-graphics/uno-sdk/pulls) for bugs and features. Any feedback is welcome at [elect86@gmail.com](mailto://elect86@gmail.com).

# Simplest hello world

            glfw.init("3.3")

            val window = GlfwWindow(1280, 720, "ImGui Lwjgl OpenGL3 example").apply {
                init()
            }
            
            glClearColor(1f, 0f, 0f, 0f)

            window.loop {
                glClear(GL_COLOR_BUFFER_BIT)
            }

## Credits:

- [Farid Zakaria](https://github.com/fzakaria) for [ascii85](https://github.com/fzakaria/ascii85)
- [Jogamp](http://jogamp.org/) for BufferedImage flipping 
