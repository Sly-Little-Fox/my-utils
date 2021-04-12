This page tries to close itself with different methods.
<script>
try {
  window.close();
} catch {}
try {
  window.open('', '_self').close();
} catch {}
</script>
