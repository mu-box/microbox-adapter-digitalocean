An implementation of the [Microbox Custom Provider](https://docs.microbox.cloud/providers/create/) spec for DigitalOcean.

## Development

### Local Server
`bundle exec puma -e development`

### Update Catalog

### Local Evars
A DigitalOcean Access Token is required to retrieve the catalog.
`microbox evar add ACCESS_TOKEN=your_digital_ocean_access_token`

### Console
`bundle exec irb -I. -r app.rb`
