
# Azure Resource naming rules
https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/resource-name-rules
This helps show the 
# Baseline naming structure
Environment > Purpose > Instance number 
I.E: PROD-FILES-001

### Azure Resources that must be globally unique
DataFactory (Alphanumerics and hyphens only)

### Azure Resources that don't allow for spaces or dashes
Storage accounts

Example: prodstorage001

### Azure Resources that don't allow capitals

### Azure Resources that allow anything
MySQL Flexible Server
prod-mysql-001

# Entra
### Entra Groups for Azure
Any Group starting with AZ is leveraged for Azure permissions.
Az - purpose

### 