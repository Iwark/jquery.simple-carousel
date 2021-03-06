jQuery Simple Carousel ![Bower Version](https://badge.fury.io/bo/jquery.simple-carousel.svg)
----

### Simple jQuery Carousel Plugin

## Installation

```
bower install jquery.simple-carousel
```

## Usage

1. Include jQuery and [jquery.finger](https://github.com/ngryman/jquery.finger).

  ```html
  <script src="../lib/jquery/jquery.js"></script>
  <script src="../lib/jquery.finger/jquery.finger.js"></script>
  ```

2. Include plugin's code:

  ```html
  <link rel="stylesheet" href="../src/css/jquery.simple-carousel.css"> 
  <script src="../src/js/jquery.simple-carousel.js"></script>
  ```

3. Call the plugin:

  ```html
    <style>
      .sc-slider{
        margin: 0 auto;
        width:  500px;
        height: 333px;
      }
    </style>

    <div class="sc-slider">
      <ul class="sc-slides">
        <li class="sc-slide">
          <a href="#">
            <img src="images/img1.png" />
          </a>
        </li>
        <li class="sc-slide">
          <a href="#">
            <img src="images/img2.png" />
          </a>
        </li>
        <li class="sc-slide">
          <a href="#">
            <img src="images/img3.png" />
          </a>
        </li>
      </ul>
    </div>

    <script>
      $(function(){

        $('.sc-slider').simpleCarousel({
          interval: 5000,
          prev: "＜",
          next: "＞"
        });

      });
    </script>
  ```

## History

Check [Releases](https://github.com/Iwark/jquery.simple-carousel/releases) for detailed changelog.

## License

[MIT License](http://iwark.mit-license.org) © Iwark