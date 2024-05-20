# Usage

### Please copy paste below code

```
module "release" {
  source  = "SashaKrav/release/helm"
  name   = "testapplication"
  namespace = "testapp"
  values_yaml = <<EOF
 EOF 
}
```
