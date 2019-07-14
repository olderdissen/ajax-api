# ajax-api

few years ago, i creates my own clone of ajax component.
before i created this script, i accessed all **onstart** and other events directly in each script.
this result in multiple create objcts.
after i invesigated a widle known public open source ajax component, i decided to create my own minimized ajax component.


	new XMLHttpRequest()
	new ActiveXObject("Microsoft.XMLHTTP")
	
	ajax({ url : 'file.php?action=info', success : document_info_success })

