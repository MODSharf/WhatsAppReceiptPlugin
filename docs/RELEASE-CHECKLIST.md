# Public Release Checklist

## Build and package
- [ ] Build from the intended source commit in Release configuration.
- [ ] Confirm exact Aronium and Windows compatibility on a clean test machine.
- [ ] Identify every runtime dependency and include only redistributable dependencies.
- [ ] Confirm Aronium assemblies are not bundled unless redistribution is explicitly permitted.
- [ ] Exclude `.vs/`, `obj/`, test harnesses, mock modules, PDBs, local settings, and development artifacts unless intentionally required.
- [ ] Package only the files needed by the verified installation procedure.
- [ ] Scan package and repository history for credentials and personal data.
- [ ] Test install, upgrade, rollback, uninstall, and a real receipt delivery flow.
- [ ] Verify no duplicate send and no sales-blocking issue in the tested scenarios.

## Release page
- [ ] Use a semantic version such as `v1.0.0`.
- [ ] Add concise release notes and known limitations.
- [ ] Attach the tested ZIP installer package.
- [ ] Publish SHA-256 checksum for the installer.
- [ ] Link the installation guide and support channel.
- [ ] State the licence and commercial terms.
