# RailsCasts Episode #370: Ransack

http://railscasts.com/episodes/370-ransack

Requires Ruby 1.9.2 or higher.


### Alternative form

```rhtml
<%= search_form_for @search do |f| %>
  <div class="field">
    <%= f.label :name_cont, "Name contains" %>
    <%= f.text_field :name_cont %>
  </div>
  <div class="field">
    <%= f.label :price_gteq, "Price between" %>
    <%= f.text_field :price_gteq %>
    <%= f.label :price_lteq, "and" %>
    <%= f.text_field :price_lteq %>
  </div>
  <div class="actions"><%= f.submit "Search" %></div>
<% end %>
```
