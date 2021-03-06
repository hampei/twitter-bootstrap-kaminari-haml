# Kaminari HAML views for Twitter Bootstrap

[twitter bootstrap](https://github.com/twitter/bootstrap) is a toolkit from Twitter designed to kickstart development of webapps and sites, including styles for [pagination](http://twitter.github.com/bootstrap/#navigation).  If you're using [kaminari](https://github.com/amatsuda/kaminari) as your pagination library, the markup in its default views won't match the selectors used by bootstrap.  This repository contains modified copies of kaminari's views that you can drop in to your ruby application to work with bootstrap.

## Installation

Simply copy app/views/kaminari to your views folder.

Adds optional data option to paginate, that will be passed to all page-links.

    = paginate @users, remote: true, data: {replace_element: '#admin_main'}

## Credits

Converted from Dat Le's [original HAML repo](https://github.com/datl/twitter-bootstrap-kaminari-haml)  
Converted from gabetax's [original ERB repo](https://github.com/gabetax/twitter-bootstrap-kaminari-views)
