# Code Igniter with gulp


This is a project set up to being used with gulp so you can develop your application faster.

### Getting Started

  1. Pull the repository
  2. Change git remote origin with following command :
```sh
$ git remote set-url origin https://github.com/USERNAME/REPOSITORY.git
```
  3. Run gulp
```sh
$ gulp
```
  4. Start developing your app!

### Files

| Type | Location |
| ---- | -------- |
| Code Igniter | */app* |
| SCSS | */scss* |
| Javascript | */js* |
| Fonts | */fonts* |

When you modify these file with gulp running it'll be handled and refresh your browser.

More info:
 - In */js* folder files that names end with **.min.js** won't be minified but just copied

### Configuration File

The configuration file is called **project-config.json** and is located in root folder

- **_dist_dir_**: The location of your apache server that serves HTTP requests 
- **_host_**: Host used to *browser-sync*
- **_port_**: Port used to *browser-sync* 
- **_debug_**: The location of your apache server that serves HTTP requests 

### Usage
 - For just run gulp in development mode
``` sh
$ gulp
```
 - Build the project (minify files etc.). Build project is in **build/** folder
``` sh
$ gulp build
```
 - Clean **dist_dir** (removes everything)
``` sh
$ gulp cleanup
```
