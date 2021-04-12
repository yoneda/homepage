# Homepage
web developper yoneda's homepage.
## Development
```
// use macOS
$ brew install sass
$ sass --watch index.scss index.css
$ open index.html
```
## Primitive Deployment
```
$ rsync -a . user@hostname:/dir/to/path
$ ssh user@hostname 'systemctl restart nginx'
```
refarence: [How To Install Nginx on Ubuntu 18.04](https://www.digitalocean.com/community/tutorials/how-to-install-nginx-on-ubuntu-18-04)

## License
MIT