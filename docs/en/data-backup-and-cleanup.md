# Data Safety Notice

Pixel Flow stores favorites, download history, and some analysis cache in your browser. Export a backup before cleanup, uninstalling the extension, clearing browser extension data, or resetting browser settings.

<div class="docs-alert docs-alert-critical">
  <strong>High-risk actions: back up first</strong>
  <p>The two actions below may remove Pixel Flow's local database. Do not continue until you have exported a backup.</p>
</div>

<table class="docs-risk-table">
  <thead>
    <tr>
      <th>Action</th>
      <th>Affects local data?</th>
      <th>Impact</th>
      <th>Recoverable?</th>
      <th>Recommendation</th>
    </tr>
  </thead>
  <tbody>
    <tr class="risk-critical">
      <td><strong>Uninstall the Chrome extension</strong></td>
      <td>Yes</td>
      <td>Chrome may clear the extension's local database</td>
      <td>Only if you have a backup</td>
      <td><strong>Export a backup before uninstalling</strong></td>
    </tr>
    <tr class="risk-critical">
      <td><strong>Clear browser extension data / reset browser settings</strong></td>
      <td>Possible</td>
      <td>May clear Pixel Flow's local database and settings</td>
      <td>Depends on whether you have a backup</td>
      <td><strong>Export a backup first</strong></td>
    </tr>
    <tr>
      <td>Clean download history in Settings</td>
      <td>Yes</td>
      <td>Deletes download history for the selected range or all history</td>
      <td>Only if you have a backup</td>
      <td>Back up before cleanup</td>
    </tr>
    <tr>
      <td>Clean favorite records in Settings</td>
      <td>Yes</td>
      <td>Deletes selected favorite records and locally stored image data</td>
      <td>Only if you have a backup</td>
      <td>Back up important assets first</td>
    </tr>
    <tr>
      <td>Delete a custom tag</td>
      <td>Partially</td>
      <td>Deletes the tag and removes it from saved images</td>
      <td>Requires recreating the tag or importing a backup</td>
      <td>Confirm the tag is no longer needed</td>
    </tr>
    <tr>
      <td>Import a backup</td>
      <td>Does not clear existing favorites</td>
      <td>Merges favorites, download history, and tags; preferences may be restored from the backup</td>
      <td>You can adjust settings afterward</td>
      <td>Confirm the backup belongs to the current account</td>
    </tr>
    <tr>
      <td>Sign out / unbind account</td>
      <td>Usually no</td>
      <td>Affects account status, PRO access, or binding method</td>
      <td>Sign in or bind again</td>
      <td>Regular backups are still recommended</td>
    </tr>
  </tbody>
</table>

## How To Back Up

Open the Pixel Flow side panel, go to Settings -> Data backup and migration -> Data backup, then export the backup package and keep it somewhere you can find later.

## Before You Continue

1. Make sure you have exported a fresh backup.
2. Make sure you can find the backup file.
3. Confirm whether the browser action affects extension data.
4. If you are uninstalling or resetting browser settings, continue only after the backup is saved.
