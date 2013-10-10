bootstrap_in_will_paginate
==========================

the style of bootstrap's paginate for will_paginate


## Usage

copy the file "bootstrap_link_renderer.rb" to your rails_path/lib

Add this line to your config/application.rb

	config.autoload_paths += Dir["#{config.root}/lib", "#{config.root}/lib/**/"]

and then in your view file

	<%= will_paginate(@users, :renderer => BootstrapLinkRenderer) %>



