<template>
  <Tutorial />
</template>

<script>
export default {
  name: 'IndexPage',
  metaInfo: {
    // if no subcomponents specify a metaInfo.title, this title will be used
    title: 'Perusahaan',
    // all titles will be injected into this template
    titleTemplate: '%s | Talenta Nusantara',
    meta: [
      { charset: 'utf-8' },
      { name: 'viewport', content: 'width=device-width, initial-scale=1' },
      {
        hid: 'description',
        name: 'description',
        content: 'my website description'
      }
    ]
  }
}
</script>
