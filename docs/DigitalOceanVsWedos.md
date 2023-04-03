# DigitalOcean vs Wedos

Date: 2.4.2023

In this article, I will compare two server providers which are DigitalOcean and Wedos. These platforms offer many other services which will not be included in this article. Therefore I will focus only on the VPS servers which they offer. More specifically for Wedos, I will focus on VPS ON service. For DigitalOcean I will focus on Droplets.

## Wedos

Link to VPS ON pricing page: https://order.wedos.cz/cs/vps-on/order.html?step=1

Here we can for example take the variant with 1 GB RAM, 25 GB SSD, 1 core and shared CPU. Without any additional services, this variant costs 2781.31 with VAT (DPH) per year. There is a fee for an IPv4 address which is 1 CZK per month. This fee is already included in the price. Additional services like weekly snapshots and DDoS protection could be bought with this service. But for purpose of comparison, I will not consider them here.

## DigitalOcean

Link to DigitalOcean pricing page: https://www.digitalocean.com/pricing/

There we can for example take the droplet variant with 1 GB RAM, 25 GB SSD and 1 core of CPU. This variant is comparable with the variant on Wedos. Without any additional services, this variant costs 5 USD per month without VAT, which is 7.26 with VAT (VAT is 21%). That is 87.12 USD per year with VAT. This amount is equal to 2041.92 in CZK.

## Comparison

On first sight, we can say that Digital ocean is cheaper by 739.39 CZK per year. But on DigitalOcean for this droplet is an outbound transfer limit of 1000 GB per month. If you will exceed this limit then you will be charged 0.01 USD per GB transferred. This is not the case on Wedos. Therefore if you will exceed the limit on DigitalOcean, you will pay more than on Wedos. But if you will not exceed the limit, then DigitalOcean is cheaper. But someone could think what if my website will be under a DDoS attack and the droplet limit will exceed by a huge amount and I will be served with an unexpected bill?

Link to the bandwidth billing explanation: https://docs.digitalocean.com/products/billing/bandwidth/

For this issue I can provide some links here:
- https://docs.digitalocean.com/products/droplets/details/limits/
- Some discussion about the limits is on this link: https://www.reddit.com/r/webhosting/comments/oxlrl2/transfer_limits_digital_ocean_and_linode/
