project('dodo-compositor', 'c', version: '0.1.0')

wlroots = dependency('wlroots')
wayland_server = dependency('wayland-server')
xkbcommon = dependency('xkbcommon')

executable(
  'dodo-compositor',
  'src/main.c',
  dependencies: [
    wlroots,
    wayland_server,
    xkbcommon,
  ],
)