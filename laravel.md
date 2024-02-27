# Laravel commands and aliases
Alias legend:
* `sa` = sail artisan
* `m` = make

To have a look which Laravel commands are available by default, run
* `php artisan`
* or `sail artisan` if you are using Sail

---
<br>

## Models

## Views
| Alias      | Command   |  Description |
| ------- | ----------- | --------------- |
| `samview`  | sail artisan make:view my-view | Create new view file in resources/views/ |
| | sail artisan view:cache | Pre-compile all views to increase app performance (use it while deploying) |
| | sail artisan view:clear | Clear view cache (if there are some problems with views) |

---
<br>

## Controllers

| Alias      | Command   |  Description |
| ------- | ----------- | --------------- |
| `samctrl`  | sail artisan make:controller | Create new controller file in app/Http/Controllers/ |

## Routes



