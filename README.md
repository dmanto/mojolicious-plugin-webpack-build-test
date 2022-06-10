# mojolicious-plugin-webpack-build-test
run build test on Mojolicious::Plugin::Webpack

- lite.pl is exactly as in webpack example:

```$> mojo webpack lite.pl``` --> runs ok

- t/build-assets.t is almost the same as suggested in Mojolicious::Plugin::Webpack (Only change is to point to lite.pl script)

```$> TEST_BUILD_ASSETS=1 prove -lv t/build-assets.t``` --> fails

