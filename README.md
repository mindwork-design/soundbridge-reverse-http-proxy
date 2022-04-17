
# mind.work_radio-proxy
nginx-proxy-settings for a Soundbridge radio, that only supports http streams, but wants to play https streams too.

context: https://mind.work/2021/01/18/rescue-of-the-soundbridge-m1001/

To use it in your own projects, replace 'localhost' in 'mind_work/etc/nginx/conf.d/default.conf' with the hostname you actually use.

Build:
  docker-compose build

Start:
  docker-compose up
