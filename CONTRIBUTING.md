Contributions adding examples of major violations are welcome!

Note that here only uses by major entities will be listed - big organizations, large enough that they definitely have enough resources to fix the problem.


Every page should have

- clear statement that what given entity is doing is illegal
- images documenting usage of OpenStreetMap data in violation of its licence (usually it is a missing attribution)
- list of attempts done to fix this

Pull requests can be opened early, but I will merge ones with delay if recent attempt to contact is really rece, to give them time to fix (at least 7 days).

For generating gif files from mp4 - see

```
ffmpeg \
  -i input.mp4 \
  -r 15 \
  -vf "scale=512:-1,split[s0][s1];[s0]palettegen[p];[s1][p]paletteuse" \
  -ss 00:00:20 -to 00:00:30 \
  output.gif
```

note that `00:00:03 -to 00:00:06` is for converting between this timestamps.

Code by "[Ciro Santilli 新疆再教育营六四事件法轮功郝海东](https://askubuntu.com/a/837574/349903)".
