Simple example of using `poetry2nix` as a flake in a subdirectory.

Enter a shell with:
```bash
cd mydir
nix develop
# test the package is in the environment
python -m helloworld.app
```

Build the package with:
```bash
nix build
# Run the app
./result/bin/helloworld
```