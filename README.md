# Mandelbrot Using Rust

This repository implement [Mandelbro set equation](<https://simple.wikipedia.org/wiki/Mandelbrot_set#:~:text=The%20Mandelbrot%20set%20can%20be,positive%20integer%20(natural%20number).>) using Rust

# How to use

```
// clone this repo
1. git clone REPO_URL

// cd to project
2. cd /mandelbrot-equation

// build the project
3. cargo build --release

// execute the bin
// list argument: COMMAND filename pixels upper_left lower_right
4. time /target/release/mandelbrot mandel.png 4000x3000 1.20,0.35 -1.0,2.0
```

After the execution process, we can see/open the image from the root folder.
