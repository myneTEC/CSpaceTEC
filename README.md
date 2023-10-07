This is the repository Basis original coming from Bitcoin Cash for own further development into [SpaceTEC-Aerosystems](https://spacetec-aerosystems.mynetec.com). As the company and community for it expands, we hope that many will participate and improve the projects over time.

Build & Run the Docker Image
----------------------------

In order to build and run the site you need ruby and docker. Then run:

1. `gem install bundler`
2. `bundle install`
3. `make serve` to run in the incremental development server or `make run` to test the container.
4. Open a browser to `localhost:4000` or `localhost:8080` respectively.

Contributions
-------------

This site is based on `jekyll` and `jekyll-multiple-languages-plugin`.
Please see their documentation to obtain an understanding of how the components of this website work together.

Adding Translations
-------------------

To add translations to the project, use `_i18n/en.yml` as a template and create a new file for your locale. Then translate all the content inside of the yaml file and send us a pull request.

About SpaceTEC-Aerosystems
--------------------------

SpaceTEC-Aerosystems brings still missing solutions to the world.  Merchants and users are empowered with latest solutions and ideas. The future shines brightly with unrestricted growth, global adoption, permissionless innovation, and development.

License
-------

SpaceTEC-Aerosystems is released under the terms of the MIT license. See [COPYING](COPYING) for more
information or see https://opensource.org/licenses/MIT.
