# BigRep Blade Material Profiles

A community-maintained archive of material profiles for BigRep's Blade slicer software.

## The Problem

Blade has a persistent issue where material profiles and print settings disappear depending on your machine selection, nozzle configuration, and software version. This behavior is inconsistent across Blade versions, sometimes requiring multiple installations just to access complete material options. This repository exists to ensure you always have access to working profiles.

## Repository Structure
```
/profiles
  /blade-x.x.x           # Organized by Blade version
    /machine-type        # e.g., ONE, STUDIO, PRO, etc.
      /nozzle-config     # e.g., 0.6mm, 1.0mm
        material-profile # Individual profile files
```

## How to Use

1. Navigate to the folder matching your Blade version and machine configuration
2. Download the material profile(s) you need
3. In Blade: `Settings > Material > Import` (or drag into the materials folder)
4. Restart Blade if profiles don't appear immediately

### Manual Profile Location

Blade typically stores profiles in:
- **Windows:** `C:\Users\<username>\AppData\Roaming\BigRep\Blade\materials`
- **macOS:** `~/Library/Application Support/BigRep/Blade/materials`

## Contributing

Have profiles that work? Please contribute!

1. Fork this repository
2. Add your profile(s) following the folder structure above
3. Include a brief note about what machine/nozzle combo you tested with
4. Submit a pull request

### When Contributing, Please Note:
- Blade version the profile was exported from
- Machine model and nozzle diameter
- Any known quirks or settings you modified

## Compatibility Notes

| Blade Version | Known Issues |
|---------------|--------------|
| x.x.x         | *Add notes as discovered* |

## Disclaimer

These profiles are community-contributed and provided as-is. Always verify settings before production prints. This repository is not affiliated with BigRep GmbH.

## License

MIT - Use freely, contribute back when you can.
