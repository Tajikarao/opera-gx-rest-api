# opera-gx-rest-api

# Objective

The purpose of this repository is to display a set of enpoints related to Opera GX.

Initially I was looking to get the endpoints related to Opera GX Corner, then I decided to get all the endpoints of the mobile application, and the installer.

The goal is not to harm the Opera company but to allow everyone to use these endpoints in their programs, for example, for a bot discord.

# mobile-tab-games

#### METHOD: GET
> The HTTP GET method requests a representation of the specified resource. [Find out more](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods/GET)

___

#### ENDPOINT:
` https://gx-proxy.operacdn.com/content/mobile-tab-games `

___

#### POTENTIAL ARGUMENTS:

```
_limit (exemple: 200)
_locale (exemple: en)
_sort (exemple: order:ASC)
```


# mobile-tab-watches

#### METHOD: GET
> The HTTP GET method requests a representation of the specified resource. [Find out more](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods/GET)

___

#### ENDPOINT:
` https://gx-proxy.operacdn.com/content/mobile-tab-watches `

___

#### POTENTIAL ARGUMENTS:

```
_limit (exemple: 200)
_locale (exemple: en)
_sort (exemple: order:ASC)
```


# mobile-tab-explores

#### METHOD: GET
> The HTTP GET method requests a representation of the specified resource. [Find out more](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods/GET)

___

#### ENDPOINT:
` https://gx-proxy.operacdn.com/content/free-games `

___

#### POTENTIAL ARGUMENTS:

```
_limit (exemple: 200)
_locale (exemple: en)
_sort (exemple: order:ASC)
```


# calendars

#### METHOD: GET
> The HTTP GET method requests a representation of the specified resource. [Find out more](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods/GET)

___

#### ENDPOINT:
` https://gx-proxy.operacdn.com/content/calendars `

___

#### POTENTIAL ARGUMENTS:

```
_limit (exemple: 200)
_sort (exemple: released_at:ASC)
```


# content trailers

#### METHOD: GET
> The HTTP GET method requests a representation of the specified resource. [Find out more](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods/GET)

___

#### ENDPOINT:
` https://gx-proxy.operacdn.com/content/trailers `

___

#### POTENTIAL ARGUMENTS:

```
_limit (exemple: 200)
_sort (exemple: order:DESC)
```

# content stores

#### METHOD: GET
> The HTTP GET method requests a representation of the specified resource. [Find out more](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods/GET)

___

#### ENDPOINT:
` https://gx-proxy.operacdn.com/content/stores?_limit=200&_sort=order:ASC&_where[_or][0][0][countries.key]=fr&_where[_or][1][0][countries.key_null]=true `



# trailers

#### METHOD: GET
> The HTTP GET method requests a representation of the specified resource. [Find out more](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods/GET)

___

#### ENDPOINT:
` https://gx-proxy.operacdn.com/trailers `

___

#### POTENTIAL ARGUMENTS:

```
_limit (exemple: 200)
_sort (exemple: order:ASC)
```


# free-games

#### METHOD: GET
> The HTTP GET method requests a representation of the specified resource. [Find out more](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods/GET)

___

#### ENDPOINT:
` https://gx-proxy.operacdn.com/content/free-games `

___

#### POTENTIAL ARGUMENTS:

```
_limit (exemple: 200)
_sort (exemple: order:ASC)
```


# upcoming-releases

#### METHOD: GET
> The HTTP GET method requests a representation of the specified resource. [Find out more](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods/GET)

___

#### ENDPOINT:
` https://gx-proxy.operacdn.com/content/upcoming-releases `

___

#### POTENTIAL ARGUMENTS:

```
_sort (exemple: order:DESC)
```

# top-2

#### METHOD: GET
> The HTTP GET method requests a representation of the specified resource. [Find out more](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods/GET)

___

#### ENDPOINT:
` https://gx-proxy.operacdn.com/content/top-2 `

___

#### POTENTIAL ARGUMENTS:

```
_sort (exemple: order:ASC)
```


# geolocation

#### METHOD: GET
> The HTTP GET method requests a representation of the specified resource. [Find out more](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods/GET)

___

#### ENDPOINT:
` https://autoupdate.geo.opera.com/geolocation `


# weather location

#### METHOD: GET
> The HTTP GET method requests a representation of the specified resource. [Find out more](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods/GET)

___

#### ENDPOINT:
` https://weather.opera-api2.com/location `

___

#### POTENTIAL ARGUMENTS:

```
id (exemple: 623)
language (exemple: en)
```


# netinstaller

#### METHOD: GET
> The HTTP GET method requests a representation of the specified resource. [Find out more](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods/GET)

___

#### ENDPOINT:
` https://autoupdate.geo.opera.com/v5/netinstaller/gx/Stable/windows/x64 `


# netinstaller verify

#### METHOD: GET
> The HTTP GET method requests a representation of the specified resource. [Find out more](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods/GET)

___

#### ENDPOINT:
` https://autoupdate.geo.opera.com/api/verify `

___

#### POTENTIAL ARGUMENTS:

```
product (exemple: Opera GX)
version (exemple: 98.0.4759.22)
```