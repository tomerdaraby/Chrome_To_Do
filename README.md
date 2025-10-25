# Chrome_To_Do
A chrome extension of a to do list that will block internet surfing other than allowed websites and will reward finishing tasks with free surfing

writing my comments for the json here cause appertnly its impossible to comment in json files :)
"manifest_version": 3 - the format version, a must for google
"icons": - icons for the extensions (in diffrent sizes)
"chrome_url_overrides": {"newtab": "todo.html"} - turns new tab to the to-do list
"permissions": - everything that we will need to manage the websites usage