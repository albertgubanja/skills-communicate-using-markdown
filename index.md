# Edit file tab,
# It is just for test


![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png "Optional image")


```python
def contact_success(request):
    social_links = SocialLink.objects.all()
    context = {
        'social_links': social_links
    }
    return render(request, 'core/contact_success.html', context)


def download_resume(request):
    resume = Resume.objects.first()  # Simplified
    context = {'resume': resume}
    return context
```


- [ ] Turn on GitHub Pages
- [ ] Outline my portfolio
- [ ] Introduce myself to the world
