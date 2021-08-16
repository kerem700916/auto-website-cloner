import requests, os, webbrowser

class clone:
    def __init__(self, url):
        self.url = url
        site = requests.get(url)
        file = open('site.html', 'a')
        file.truncate(0)
        file.write(site.text)
        path = os.getcwd() + '/site.html'
        webbrowser.open(path)
# Easy
