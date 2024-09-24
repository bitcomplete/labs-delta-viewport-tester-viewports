# Labs: Viewport Tester
This repository contains a JSON file (see `items.json`) which lists modern /
up-to-date viewports. This is used extensively in our product
[https://viewport-tester.com/](https://viewport-tester.com/), which allows you
to quickly test viewports and breakpoints for your website / webpage.

Feel free to use this data (licensed under MIT) for your own projects (and
submit a PR to this `README.md` file so we can link to your project).

Additionally, we're sure our list of devices / viewports is missing some. If so,
please submit a PR so we can maintain this JSON database of viewports.


## Share your ideas/feedback
You can reach us at
[hello@viewport-tester.com](mailto:hello@viewport-tester.com) with any ideas,
questions, or issues you've noticed that you'd prefer not to post on our
[issues](https://github.com/bitcomplete/labs-delta-viewport-tester-viewports/issues)
page.


## Caveats
- [Viewport Tester](https://viewport-tester.com/) works similar to how the
Chrome Inspector's Device Inspector works: it sets the frame dimensions to the
exact width and height. An issue with this is that almost all devices, by
default, include a header (e.g. tabs, URL input, etc). Because of this, the
viewport dimensions you see are not exactly representative of the real-world.
Generally, it represents the correct width (which is the most important part
viewport/breakpoint testing), but what you see within the viewport is often more
than what a real-world scenario would showcase. We plan on addressing this in
future, with properties that reflect the header offset heights for different
devices.
- There is a small width pixel difference between what's represented in
[Viewport Tester](https://viewport-tester.com/), and real world scenarios. This
has to do with how scrollbars are represented within iframes, versus native
devices. Specifically, within iframes scrollbars are allocated width, whereas
most mobile devices overlay the scrollbar over top of the content. This will
also be addressed in future versions of the data set, whereby we specify the
scrollbar overlay behaviour.


## Preview
Preview of how this data is used in
[Viewport Tester](https://viewport-tester.com):
![image](https://github.com/user-attachments/assets/7cbabf12-3c2b-42d5-b412-b312b2d133be)

[Bit Complete Inc.](https://bitcomplete.io/)
