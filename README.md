# helm-gundb-backend-mongo

> 
> A Helm chart to deploy on Kubernetes a GunDB instance with Mongo backend.
> 
> 🚀 Powered by the [Tamia Team](https://tamia.team).
> 
> **Contributing 🙂 and/or [#support-team-tamia]((https://github.com/sponsors/tamia-team)) 🥰 are welcome!**
> 

## Table of contents

- [Synopsis](#synopsis)
- [Usage](#usage)
  - [Clone from git](#clone-git)
  - [Deploy chart as a release](#deploy-chart)
  - [Undeploy release](#undeploy-release)

[Support the Tamia Team!](#support-team-tamia)

## Synopsis <a name="synopsis"></a>

A Helm chart to deploy on Kubernetes a GunDB instance with Mongo backend.

## Usage <a name="usage"></a>

### Requirements for this documentation

```
export RELEASE_NAME="my-gundb"
export PROJECT_HOME="/home/username/path/to/helm/chart/"
export KUBERNETES_NAMESPACE="gundb"
```

### Clone from git <a name="clone-git"></a>

```
git clone git@github.com:tamia-team/helm-gundb-backend-mongo.git ${PROJECT_HOME}
```

### Configure values

Configure the following Helm charts values for your context:

```
```

### Deploy chart as release <a name="deploy-chart"></a>

```
cd "${PROJECT_HOME}"
helm install "${RELEASE_NAME}" . -n ${KUBERNETES_NAMESPACE} 
```

### Undeploy release <a name="undeploy-release"></a>

```
helm uninstall "${RELEASE_NAME}" -n ${KUBERNETES_NAMESPACE} 
```

## License

>
> Copyright 2023 [Tamia SAS](https://tamia.team), Saint-Etienne 42100, France 🇫🇷
>
> Permission is hereby granted, free of charge, to any person obtaining a copy
> of this software and associated documentation files (the “Software”), to
> deal in the Software without restriction, including without limitation the
> rights to use, copy, modify, merge, publish, distribute, sublicense, and/or
> sell copies of the Software, and to permit persons to whom the Software
> is furnished to do so, subject to the following conditions:
>
> The above copyright notice and this permission notice shall be included in
> all copies or substantial portions of the Software.
>
> THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
> IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
> FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
> AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
> LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
> FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
>
> Except as contained in this notice, the name of the "Tamia SAS" shall not
> be used in advertising or otherwise to promote the sale, use or other dealings
> in this Software without prior written authorization from the Tamia SAS company.
>

---

# Support the Tamia Team! <a name="support-team-tamia"></a>

You can support our open-sourced work about various domains us in multiple ways:

- **Contribute to our open-source projects** by reporting bugs, fixing bugs, or developing new features.
- **Sponsor one or all of our published open-source projects through donations.**

## Become a Sponsor

Whether you are a customer or not, you can support our work by becoming an official sponsor. Please contact us for more details.

## Make a Donation

### Donation Process

If you would like to make a donation to support the open-source initiatives of the [Tamia Team](https://tamia.team), please follow this process:

1. Send us an email including the following information:

  - The exact amount of the donation in the selected cryptocurrency.
  - The following details:
    - First name
    - Last name
    - Company (if applicable)
    - Postal address
    - Zipcode
    - City
    - Country
    - Phone number
    - Email address

2. After receiving our confirmation via email, we will invite you to transfer the donation amount.
3. Proceed with the transaction.
4. Upon receiving your donation, an official proof document from Tamia SAS company will be generated and sent to you.

### Tamia Team Wallets

- [BTC (Bitcoin) - bc1qyp27fvanqhupea9vve7t6sdctx6mnqgqhcakz3](bitcoin:bc1qyp27fvanqhupea9vve7t6sdctx6mnqgqhcakz3?message=Donations)
- 
