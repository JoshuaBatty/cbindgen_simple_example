# cbindgen_simple_example
smallest possible example for using cbindgen to generate a C to Rust FFI 


See [this gist](https://gist.github.com/JoshuaBatty/fe1fa83774ecc2afbd700729ea2de9f4) for an example of how to link to Unreal Engine 4 the resulting .lib and .hpp file to gets generated when `cargo build --release` is run. 

In the `Source` folder of your UE4 project, create a new folder called `ThirdParty`. Then create a new folder called `SomeProjectName`. Then inside there, create 2 folders, one called `lib` and another called `include`. Put the generated .hpp file in the `include` folder and the .lib file in the `lib` folder. 