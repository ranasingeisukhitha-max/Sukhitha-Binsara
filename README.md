<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Sukhitha Binsara - Office</title>
<link rel="stylesheet" href="https://unpkg.com/@univerjs/presets/lib/styles.css" />
<style>html,body,#app{height:100%;margin:0}</style>
</head>
<body>
<div id="app"></div>
<script type="module">
import { createUniver } from 'https://esm.sh/@univerjs/presets@0.10.0';
import { UniverSheetsCorePreset } from 'https://esm.sh/@univerjs/preset-sheets-core@0.10.0?external=@univerjs/presets';
const { univerAPI } = createUniver({
  presets: [[UniverSheetsCorePreset, { container: 'app' }]],
});
univerAPI.createUniverSheet({ name: 'Sukhitha Sheet' });
</script>
</body>
</html>