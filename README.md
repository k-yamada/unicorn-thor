# Installation

~~~
$ cd your_rails_app
$ wget https://github.com/k-yamada/unicorn-thor/blob/master/unicorn.thor
~~~

set your app name to unicorn.thor

~~~
$ vim unicorn.thor
class Unicorn < Thor
  APP_NAME = "your_app_name"
~~~

# Usage

~~~
$ thor unicorn:start
$ thor unicorn:stop
$ thor unicorn:restart # graceful restart
$ thor unicorn:hup     # reload setting
~~~


