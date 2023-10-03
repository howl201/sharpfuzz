# SharpFuzz samples

Test of MemoryPack

Example usage:

```powershell
scripts/fuzz.ps1 src/ProtobufNet/ProtobufNet.Fuzz.csproj `
    -i src/ProtobufNet/Testcases
```

Example usage with a dictionary file:

```powershell
scripts/fuzz.ps1 src/Markdig/Markdig.Fuzz.csproj `
    -i src/Markdig/Testcases `
    -x dictionaries/markdown.dict
```

The fuzzing script ([fuzz.ps1](https://github.com/Metalnem/sharpfuzz/raw/master/scripts/fuzz.ps1))
is located in the main [SharpFuzz](https://github.com/Metalnem/sharpfuzz) repo.
