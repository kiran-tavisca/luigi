<section class="fd-section">
  <div class="fd-section__header">
    <h1 class="fd-section__title">Sample 2</h1>
  </div>
  <div class="fd-panel">
    Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat.
  </div>
</section>


<script>
	import LuigiClient from '@kyma-project/luigi-client';

	function showAlert() {
		LuigiClient.uxManager().showAlert({text: 'Hello World!'});
	}
</script>
