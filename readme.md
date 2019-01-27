# bootstrap-social #
*Social network buttons for Bootstrap 4 using Fontawesone icons*

**bootstrap-social** is a add-on to **Bootstrap** to add utility to its button system to integrate painlessly social networks.

## Installation ##

### Include stylesheet ###
```html
<link href="bootstrap-social.css" rel="stylesheet" />
```

Include the **bootstrap-social** stylesheet in the head. *it requires the original Bootstrap stylesheet to work*

```html
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.2.1/css/bootstrap.min.css" />
```

## Documentation ##

**bootstrap-social** works with the [**Bootstrap** button system](https://getbootstrap.com/docs/4.1/components/buttons/) : `class="btn"`. **bootstrap-social** uses the right color of the social network. You can use [FontAwesome](https://fontawesome.com/icons?d=gallery) tags to add the image to your button.

### Classic ###

Add `btn-social` to have a classic button with text **+** `btn-<your network name>`

 For Facebook
```html
    <a class="btn btn-social btn-facebook">
	<i class="fab fa-facebook-f"></i>
	Login via Facebook
    </a>
```
 It works with any image or tag :
```html
    <a class="btn btn-social btn-google">
	<img src="img/btn_google.svg">
	Login via Google
    </a>
```
### Icon only ###

Should you need only a square button dispalying the icon of you favorite network, use `btn-social-icon` :
```html
    <a class="btn btn-social-icon btn-linkedin">
       <i class="fab fa-linkedin-in"></i>
    </a>
```
### Outline buttons ###


```html
    <a class="btn btn-social-icon btn-linkedin">
       <i class="fab fa-linkedin-in"></i>
    </a>
```

### Sizes ###

### Button group ###
Bootstap propose the option the group buttons. In that case, **no need to use** `btn-social` or `btn-social-icon`, just put `btn-<your network name>` in a div with `btn-group` *(as explained in the [Bootstrap documentation](https://getbootstrap.com/docs/4.1/components/button-group/))*
```html
    <div class="btn-group">
    	<button type="button" class="btn btn-linkedin">
	    <i class="fab fa-linkedin-in"></i>
    	</button>
    	<button type="button" class="btn btn-viadeo">
            <i class="fab fa-viadeo"></i>
    	</button>
    	<button type="button" class="btn btn-github">
            <i class="fab fa-github"></i>
    	</button>
    </div>
```

#### Vertical variation ####

As explained in the [Bootstrap documentation](https://getbootstrap.com/docs/4.1/components/button-group/#vertical-variation), a vertical variation exists for button group and it works just the same.
```html
    <div class="btn-group-vertical">
    	<button type="button" class="btn btn-linkedin">
    		<i class="fab fa-linkedin-in"></i>
    	</button>
    	<button type="button" class="btn btn-viadeo">
    		<i class="fab fa-viadeo"></i>
    	</button>
    	<button type="button" class="btn btn-github">
    		<i class="fab fa-github"></i>
    	</button>
    </div>
```

## Supported social networks ##

- Adn
- Bitbucket
- Discord
- Dropbox
- Facebook
- Flickr
- Foursquar
- Github
- Google
- Instagram
- Linkedin
- Microsoft
- Odnoklassniki
- Openid
- Pinterest
- Reddit
- Soundcloud
- Tumblr
- Twitter
- Viadeo
- Vimeo
- Vk
- Yahoo
