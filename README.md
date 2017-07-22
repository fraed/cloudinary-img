[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/fraed/cloudinary-img)

# Project Name

Polymer wrapper for cloudinary image service. http://cloudinary.com/

## Installation

bower install cloudinary-img

## Demo

<!--
```
<custom-element-demo>
  <template>
    <link rel="import" href="cloudinary-img.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<cloudinary-img
  cloud-name="euphorika"
  path="v1479480680/klfsd9yhnvdcns4ti8w1.jpg"
  transformation-params="r_10"
  alt="Rounded Corners"></cloudinary-img>
<cloudinary-img
  cloud-name="euphorika"
  path="v1479480680/klfsd9yhnvdcns4ti8w1.jpg"
  transformation-params="w_120,h_120,c_crop,g_face"
  alt="Face Finding"></cloudinary-img>
```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## License

MIT
