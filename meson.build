project('org.gnome.Papers',
  meson_version: '>= 0.59.0'
)

subdir('data')

gnome = import('gnome')
gnome.post_install(
  gtk_update_icon_cache: true
)
