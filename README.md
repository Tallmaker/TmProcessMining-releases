# Tm Process Mining

Tm Process Mining is a process mining framework and a set of visualization extensions for Qlik Cloud Analytics.

## Downloads

Each GitHub release in this repository holds these files:

- `TmProcessMining-script-<version>.zip`: the load-script framework.
- `tm-pm-<name>-<version>.zip`: one archive for each of the nine visualization extensions.
- A `.sha256` file for each archive.

Download the files from the [Releases](../../releases) page.

## Verify an archive

Verify each archive before you install it.

1. Download the archive and its `.sha256` file into the same folder.
2. On macOS or Linux, run `shasum -a 256 -c <archive>.sha256`.
3. On Windows, run `certutil -hashfile <archive> SHA256` and compare the result with the text in the `.sha256` file.
4. Install the archive only if the values are equal.

## Install an extension in Qlik Cloud

1. Open the Management console.
2. Select **Extensions**.
3. Select **Add** and choose the extension archive (`tm-pm-<name>-<version>.zip`).
4. Open an app in edit mode. The extension appears in the Assets panel under Custom objects.

Do not unzip the archive. Qlik Cloud reads the zip file as it is.

## Licensing

Each extension checks a licence file. An extension without a valid licence file shows a message that says what is wrong and what to do.
