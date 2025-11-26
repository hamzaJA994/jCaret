The app is designed to support both ar and en 

التطبيق مصمم ليدعم اللغتين العربية والإنجليزية - تم بحمدالله -.

<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8">
		<meta name="viewport" content="width=device-width, initial-scale=1.0">
		<title>jCaret Editor</title>
		<!-- include tailwind and google fonts as in attached html file here -->
		<link href="jCaret.css" rel="stylesheet" type="text/css">
		<script src="jCaret.js" type="text/javascript"></script>
	</head>
	<body class="bg-gray-100 flex items-center min-h-screen p-4 md:p-8">
		<div id="editor-container" class="w-full max-w-3xl bg-white rounded-xl overflow-hidden border border-gray-400" style="display: none;"></div>
    	<script>
    		const myEditor = new jCaret('#editor-container', {
		        // language is 'en' by default if not specified
		        //language: 'ar', // /*en*//*ar*/
		        width: '800px', // Overrides max-width to 800px
		        height: '400px', // Sets min-height to 400px
		        heightMode: 'fixed', // Editor will grow with content for /*min*/ Or /*fixed*/ for auto overflow-y
		        useLocalStorage: true, // /*true*/ Or /*false*/ for saving editor contents on page reload
		        borderRadius: '10px' // Sets Container border-radius px
		    });
    	</script>
    
    </body>
</html>
