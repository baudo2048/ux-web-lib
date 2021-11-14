# ux-web-lib
UX Components for webflow and rest services


# Install
already installed with ux-cli

# Usage

document.json('https://katecode.herokuapp.com').then(data => console.log(data))

document.em('eventName', {name:'joe'})

document.register('eventName', function(ev){console.log(ev.details.name)})

