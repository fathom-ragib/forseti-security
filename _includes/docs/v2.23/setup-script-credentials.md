Terraform uses an IAM Service Account to deploy and configure resources on behalf of the user.  The Service Account and required APIs can be setup automatically with a provided script on the 
[Forseti Terraform Github repository](https://github.com/forseti-security/terraform-google-forseti/blob/master/helpers/setup.sh). 
The Service Account and required APIs can also be configured manually by reviewing the [Requirements](https://forsetisecurity.org/docs/latest/setup/install.html#requirements) to deploy Forseti with Terraform.
Alternatively, if you are an Org Admin, you can use your own credentials to install Forseti.

```bash
git clone --branch module-release-5.0.0 --depth 1 https://github.com/forseti-security/terraform-google-forseti.git
```

```bash
cd terraform-google-forseti
```