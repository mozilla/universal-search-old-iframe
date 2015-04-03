# autocomplete-iframe
the iframe that we put inside the autocomplete dropdown

## how to use with your custom gecko

1. configure your computer's web server to serve this file from someplace on localhost
2. grab the `first-throwaway-prototype` branch of [mozilla/universal-search-gecko-dev](https://github.com/mozilla/universal-search-gecko-dev/tree/first-throwaway-prototype)
3. follow [these instructions](https://github.com/mozilla/universal-search-content/tree/444a5e4c646e9523e8835de8c662567ee74cf2e6#how-to-use-with-your-custom-gecko) to set prefs in gecko so that it can find the iframe
4. build gecko-dev and bask in our collective glory

## documenting the postmessage API with the autocomplete code

https://gist.github.com/6a68/48bf56e5b66e8631b522
