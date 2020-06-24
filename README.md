HTML код:

```php
<div class="info">
	<div class="info-header">
		<div class="info-header-tab">...</div>
		...
	</div>
	<div class="info-tabcontent fade">...</div>
	<div class="info-tabcontent fade">...</div>
</div>
```

Анимация:
```php
.fade {
  -webkit-animation-name: fade;
          animation-name: fade;
  -webkit-animation-duration: 2.5s;
          animation-duration: 2.5s;
  -webkit-animation-name: fade;
  -webkit-animation-duration: 2.5s;
}
@-webkit-keyframes fade {
  from {
    opacity: 0.1;
  }
  to {
    opacity: 1;
  }
}
@keyframes fade {
  from {
    opacity: 0.1;
  }
  to {
    opacity: 1;
  }
}
```
