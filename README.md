<<WE CAN EXECUTE ARM TEMPLATES THROUGH POWERSHELL/PORTAL/>>


******FROM LOCAL STORAGE******

New-AzResourceGroupDeployment -Name ExampleDeployment -ResourceGroupName ExampleResourceGroup `

  -TemplateFile <path-to-template> `
  
  -TemplateParameterFile <path-to-template>
  
  
  
****** FROM FILE URI********
  
New-AzResourceGroupDeployment -Name ExampleDeployment -ResourceGroupName ExampleResourceGroup `
  
  -TemplateUri <FILE URL> `
  
  -TemplateParameterUri <FILE URL>
  
  
****** THROUGH PORTAL ******
  
1.In a web browser, go to the Azure portal and sign in
  
2.From the Azure portal menu, select Create a resource
  
3.In the search box, type "TEMPLATE DEPLOYMENT"
  
4.just Load file chack and create it
