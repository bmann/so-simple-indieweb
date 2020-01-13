# So Simple IndieWeb Template

Based on the So Simple Theme and meant to be integrated with IndieKit as a micropub endpoint.

Using [@mmistakes So Simple theme](https://github.com/mmistakes/so-simple-theme), setup as a gem-based theme with the local overrides to get IndieWeb integration working correctly.

Currently being deployed to Netlify, will look at making this Github Pages compatible by default as well.

# IndieKit

[IndieKit is an IndieWeb publishing toolkit](https://paulrobertlloyd.github.io/indiekit/), written by [@paulrobertlloyd](https://github.com/paulrobertlloyd).

It is [easy to deploy using Heroku](https://paulrobertlloyd.github.io/indiekit/deploy). This template already has the proper link headers included, just edit your `_config.yml` to include the address of your Heroku server.

## IndieKit Server Notes

I ended up hacking the core server of IndieKit. Reading remote config didn't work, checking in a config file to the IndieKit on Heroku did work. Hacked the core templates and defaults file and it works.

Timezone offset can be set on the server by entering in a [TZ variable on env vars in Heroku](https://github.com/paulrobertlloyd/indiekit/issues/114#issuecomment-558206931).


