# Makya Api Gateway

## Getting started

1. Rename the `.env.sample` file to `.env``
2. Set the environment value as need (Contact Iktos to get the Authentication Token and URL)
3. Edit the `acl.yaml` to register your APIs. A sample API is provided as an example (see note below)
4. (Optional) If you don't wish to use ACL files, edit the docker-compose file to remove the mounted volume
5. Run the API Gateway with the command `docker compose up`


## Example API

This package is distributed with an example API that computes the SA Score value.
The source code of the API can be found and rebuilt from [here](https://github.com/iktos/makya-api-sa-score)

It can be safely removed from the compose file if not needed.

## Disclaimer

This source code project is provided as an example for educational and illustrative purposes only. While efforts have been made to ensure the accuracy and reliability of the code, no guarantee is made regarding its suitability for any specific purpose.

By accessing and using this source code, you agree that:

1. The code is provided "as is" without warranty of any kind, express or implied.
2. You acknowledge that you are solely responsible for any consequences resulting from the use of this code.
3. The author(s) and contributors of this code shall not be liable for any direct, indirect, incidental, special, exemplary, or consequential damages (including, but not limited to, procurement of substitute goods or services; loss of use, data, or profits; or business interruption) arising in any way out of the use of this code, even if advised of the possibility of such damage.
4. Copyright © 2024 Iktos. All rights reserved.

  
This disclaimer does not limit or exclude any liability for death or personal injury resulting from negligence, fraud, or any other liability that cannot be excluded or limited under applicable law.

Use of this source code project implies acceptance of these terms.
