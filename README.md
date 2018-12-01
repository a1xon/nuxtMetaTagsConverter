# nuxtMetaTagsConverter
Convert meta tags to nuxt style with this simple regexpression

`/<meta\s*?(.*?)\s*?=\s*?["'](.*?)["']\s*?(.*?)\s*?=\s*?["'](.*?)["']\s*?/?>/ig`

replace with`

`{ hid: '$2', $1: '$2', content: '$4' }`
