# README

This is chat demo by Rails5 ActionCable + ActiveJob

# DOC

http://railscasts-china.com/episodes/action-cable-rails-5
http://guides.rubyonrails.org/action_cable_overview.html

# Q&A

Started GET "/cable/" [WebSocket] for ::1 at 2016-08-11 14:10:55 +0800
Request origin not allowed: http://localhost:4000
Failed to upgrade to WebSocket (REQUEST_METHOD: GET, HTTP_CONNECTION: Upgrade, HTTP_UPGRADE: websocket)
Finished "/cable/" [WebSocket] for ::1 at 2016-08-11 14:10:55 +0800

config/environments/development.rb
config.action_cable.disable_request_forgery_protection = true

