# swift-build-tool

Compile using 

    swift build -Xlinker -lcurses -Xlinker -lsqlite3
    
With this hack in swift build:

    args += ["-I", path.source.parentDirectory + "/include"]
