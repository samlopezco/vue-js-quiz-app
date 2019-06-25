<template lang="pug">
    .container
        b-nav(tabs)
            b-nav-item(disabled)
                b Vue Quiz App using opentdb API
            b-nav-item(disabled) Counter: {{numCorrect}} / {{numTotal}}
</template>
<script>
export default {
    props: [
        'numCorrect',
        'numTotal'
    ]
}
</script>
