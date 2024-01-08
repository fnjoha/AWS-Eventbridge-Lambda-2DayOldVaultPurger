The code base is to delete AWS backup Recovery Points older than 2 days. 
You must set up an EventBridge to trigger daily and then a lambda function to exececute code which will purge AWS backup Vault Recovery points older than 2 days.
