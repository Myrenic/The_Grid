# <span style="color:#026873;">The_Grid</span> | <span style="color:#F2A007;">Homelab as code</span>

This project manages my homelab using Infrastructure as Code with **<span style="color:#026873;">Talos</span>**, **<span style="color:#04BFBF;">ArgoCD</span>**, and **<span style="color:#F2A007;">Terraform</span>**.

## <span style="color:#026873;">Bootstrap the cluster</span>

```bash
git clone https://github.com/Myrenic/The_Grid
cd ./The_Grid/bootstrap/terraform/ENCOM/
. ./set_proxmox_creds.sh

terraform init
terraform plan # optional
terraform apply

. ./import_config.sh
```

## <span style="color:#026873;">Tron Inspiration</span>

As you might have noticed, this entire setup is heavily inspired by Tron. From the naming conventions like The_Grid and ENCOM, to the color-themed elements in the README, everything is a nod to the digital world of Tron.

If you’re a fan of neon grids, sleek interfaces, and the idea of a fully controlled digital environment, you’ll feel right at home here. This homelab is designed to give the same sense of control and order.