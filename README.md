# Beat Saber Overlay

A web-based overlay for Beat Saber

![preview](https://i.imgur.com/Ge6t1fY.png)

## Installation (OBS)

1. Download and install the [BeatSaberHTTPStatus plugin](https://github.com/opl-/beatsaber-http-status/releases)
2. Create a Browser source

![image](https://i.imgur.com/WyTjdtd.png)

3. Set the URL as `https://overlay.theno.ninja/` and the size equal to your canvas size (1280x720, etc.)

![image](https://imgur.com/KxowYrw.png)

4. (Optional) For 1080p canvases, add the `scale` modifier (ex. `https://overlay.theno.ninja/?modifiers=scale`) to scale the overlay by 1.5x

## Options

Options are added to the URL query as such:

```
https://overlay.theno.ninja/?modifiers=scale,rtl
```

### `ip` and `port`

Listen to events from another IP and/or port. Add it with a plus if you already have modifiers
```
https://overlay.theno.ninja/?modifiers=scale+ip=127.0.0.1
```

### `modifiers`

Multiple modifiers can be seperated with commas.

- `top`
	* Moves the overlay to the top and reverses the layout vertically
- `rtl`
	* Moves the overlay to the right and uses right-to-left text
- `scale`
	* Scales the overlay by 1.5x, for use on 1080p canvases
- `test`
	* Makes the background black, for testing purposes

## Development
You can make changes to the project and even host it yourself. Just make sure you have the requirements and follow the instalation steps below.

### Requirements
- [NPM](https://www.npmjs.com/) (Included when you install NodeJS)
- [NodeJS](https://nodejs.org/en/)

### Instalation
Open CMD, powershell, or terminal and enter:
```
npm install
```
And to start the server run
```
npm start
```

# Credits
[Reselim](https://github.com/Reselim) for creating the project
