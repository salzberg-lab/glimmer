# How tro complite the code

```bash
# Go to the directory containing the Makefile
cd SimpleMake

# Compile the source code and create the executables
make

# Move to the directory containing the compiled binaries
cd ../bin

# List the generated executable files with details
ls -l

# Add the absolute path of the bin directory to PATH for this shell session
export PATH="$PATH:$(pwd -P)"
```
