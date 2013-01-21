Make sure that your comments code is in a template called comments.php.

Where you would normally display your comments, put 

```php
<?php $theme->comments( $post ); ?>
```

If there are native Habari comments on your post, these will be displayed,
along with the native comment form. Otherwise, Disqus comments will be used.

*Note:* This plugin is a dirty hack that was written before Disqus published their API.
It is out of date and in some ways broken. See [#1](https://github.com/habari-extras/disqus/issues/1).
