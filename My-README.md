# Notes

## Initial setup

- `dotnet tool restore` reads manifest from file `.config/dotnet-tools.json`.
- `dotnet fake build` reads information from
    - `build.fsx`
    - `paket.lock`
    - ???
- `dotnet fake build` creates the following folders:
    - `deploy`
    - `.fable`
    - `.fake`
    - `node_modules`
    - `paket-files`

