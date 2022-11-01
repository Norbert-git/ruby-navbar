# README

create a file in app/viwes/home Let's call it  _navbar.html.erb

Go to app/viwes/home/layouts and use this file <%= render 'home/navbar' %> within the body tag

Go to getbootstrap.com/docs/4.5/components/navbar
Pick a nav bar copy and paste the code in the  _navbar.html.erb file

Now there is a navbar on top of all pages

Remove anything not needed

Connect the links to work:

- <%= link_to 'Name of the App', root_path, class:'navbar-brand'%>

- <%= link_to 'About', home_about_path, class:'nav-link'%>

Where do you get the root_path, and the home_about_path ?

- Go to Terminal type in rails routes scroll up and will see the pages were created. All you do add  _path after. Example root_path or home_about_path.
