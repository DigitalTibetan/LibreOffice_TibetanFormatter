# LibreOffice Tibetan Formatter

## Build

To build a new release, simply create a ZIP of the content of the plugin directory:

```bash
cd LO_plugin
zip -r ../TibFormat.oxt *
cd ..
```

The resulting `TibFormat.oxt` can then be installed as LibreOffice extension. In LibreOffice, use `Tools, Extension Manager..., Add` and select `TibFormat.oxt`. After a restart, a new LibreOffice menu item `Tibetan` is available.

## Documentation

See [Tibetan formatting LibreOffice extension](https://digitaltibetan.github.io/DigitalTibetan/docs/tibetan_formatting_libreoffice_extension.html).
## License

(c) Rigpa IT 2008-2011, Eszter Hoffmann, licensed under GPL 3.0.

## Release history

- Version 1.1.503 (2020-Apr-03): Syntax fix contributed by 陳乙賓, (ReplaceInRenge -> ReplaceInRange)
- Version 1.1.502 beta (2011-Jun-09): Extension is now in OXT format and supports also LibreOffice and OpenOffice >=3.3. The extension should now work with all versions of OpenOffice >=3.0.1
- Version 1.1.5 beta: Rinchen Spungs Shad replaced also after ga and ka. This can be changed by editing a flag, in the macro. A dialog will be implemented in the future.
- Version 1.1.2 beta: There was an infinite number of combination of cases, exceptions and developing mistakes... Another bug was fixed, and now (as always) hopefully it will be stable and well functioning at all times in all texts.
- Version 1.1.1 beta: More bugs that made the extension unstable were fixed. Still some instability might be experienced. We welcome all feedbacks. More menu points and new options are implemented. Please see the function description above for more details.
- Version 1.1.0 beta: Some important bugs were fixed, so that it is more stable now. Rinchen spungs shad are correctly (not)replaced also after ka and ga. Bigger flexibility in supporting multiple spaces as well as different shad alignments.
- Version 1.0.2 beta: An add on version is implemented. A 'Tibetan' menu appears between the 'Tools' and 'Window' menus. Display Unicode Character code dialog changed.
