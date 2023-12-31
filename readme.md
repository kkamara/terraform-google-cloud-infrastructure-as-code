<img src="https://github.com/kkamara/useful/raw/main/movies.png" alt="movies.png" width=""/>

# terraform-google-cloud-infrastructure-as-code

Terraform infrastructure as code with Google Cloud Platform services: Cloud DNS API, Compute Engine API and IAM API.

* [Installation](#installation)

* [Usage](#usage)

* [Misc](#misc)

* [Contributing](#contributing)

* [License](#license)

## Installation

Create environment file.

```bash
touch terraform-with-gcp/infra/terraform.tfvars
```

```
# terraform-with-gcp/infra/terraform.tfvars
gcp_service_key = ""
gcp_project = ""
gcp_region = ""
```

Initialise terraform.

```bash
cd terraform-with-gcp/infra
terraform init
# View predeploy plan.
terraform plan
```

## Usage

```bash
terraform apply
```

```bash
terraform destroy
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[BSD](https://opensource.org/licenses/BSD-3-Clause)
