# LotusOak.github.io

This is the default GitHub Pages repository for the LotusOak organization. It provides a redirect to the main Lotus Oak Foundation website.

## Purpose

This repository exists to resolve the DNS configuration for `lotusoak.org`, which points to `lotusoak.github.io`. The site automatically redirects visitors to the main foundation website at [LotusOakFoundationWebsite](https://github.com/LotusOak/LotusOakFoundationWebsite).

## Technical Details

- **Domain**: lotusoak.org
- **DNS CNAME**: lotusoak.org → lotusoak.github.io
- **Redirect Target**: https://lotusoak.github.io/LotusOakFoundationWebsite/
- **GitHub Pages**: Enabled on main branch

## Related Repositories

- [LotusOak/LotusOakFoundationWebsite](https://github.com/LotusOak/LotusOakFoundationWebsite) - Main foundation website
- [LotusOak/root](https://github.com/LotusOak/root) - Root monorepo

## Website Architecture

This redirect setup allows the organization to maintain a clean domain structure while keeping the actual website content in a dedicated repository with its own development workflow.