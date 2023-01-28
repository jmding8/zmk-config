from Windows CMD:
cd zmk\app
west build -d build/left  -p -b nice_nano_v2 -- -DSHIELD=mercury-u_left
west build -d build/right -p -b nice_nano_v2 -- -DSHIELD=mercury-u_right