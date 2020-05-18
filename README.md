# Node + Bootstrap framework template

### This is a simple template for getting up and running with [Bootstrap](https://getbootstrap.com/)</a>

Built on [nodejs](https://nodejs.org/en/) and [expressjs](https://expressjs.com/) v4.17.1

404 error asset from [https://unsplash.com/](https://unsplash.com) by [Rémi Jacquaint
](https://unsplash.com/@jack_1?utm_medium=referral&utm_campaign=photographer-credit&utm_content=creditBadge)


| Software  | Version | Documentation                                                                                                                      |
| :-------: | :-----: | :--------------------------------------------------------------------------------------------------------------------------------: |
| jQuery    | 3.5.1   | [https://api.jquery.com/](https://api.jquery.com/)                                                                                 |
| Popper.js | 1.16.0  | [https://popper.js.org/](https://popper.js.org/)                                                                                   |
| Bootstrap | 4.5.0   | [https://getbootstrap.com/docs/4.5/getting-started/introduction/](https://getbootstrap.com/docs/4.5/getting-started/introduction/) |

### Using this template

Copy `index.html` to another file in `views`, for instance `anotherfile.html`.  Then add another route in `routes.js`:

```sh
router.get('/somelocation', function(req, res) {
  res.sendFile(views + '/anotherfile.html')
})
```
