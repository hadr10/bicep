# bicep
Deploy to azure
```
az deployment group create --resource-group MyResourceGroup --template-file main.bicep --parameters dev.bicepparam
```

```
az deployment group create --resource-group MyResourceGroup --template-file storage.bicep
```

bicep to arm
```
bicep build storage.bicep
```

arm to bicep
```
bicep decompile
```