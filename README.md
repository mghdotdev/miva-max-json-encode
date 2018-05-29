Place both the uncomplied `.mv` file and the complied `.mvc` file within the `/mm5/5.00/` folder on your server.

Replace `mm5` with whatever folder represents your Miva installation.

Example code snippet usage:
```
<mvt:do file="g.Module_Root $ 'max-json-encode.mvc'" name="l.output" value="JSON_Encode( l.variable )" />
```