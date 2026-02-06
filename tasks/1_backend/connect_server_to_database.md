# Connect Server To Database

- [ ] Navigate to “Database Deployments”
- [ ] Click “Connect”
- [ ] Click “Connect Your Application”
- [ ] Select “C# / .NET” for the driver
- [ ] Select “2.13 or later” for the version
- [ ] Copy the connection string
- [ ] Add the connection string to `Secrets.json`

```json

mongodb+srv://MAJI-26:<db_password>@cluster0.kcnzwxm.mongodb.net/?appName=Cluster0
{
  "ConnectionStrings": {
    "CommBank": "{CONNECTION_STRING}"
  }
}
```
