<template>
<v-data-table
:headers="headers"
:items="users"
:items-per-page="5"
class="elevation-1"
>

</v-data-table>
</template>
<script>
export default {
    name:"UsersTable",
    props:{
        users:{
            type:Array
        },
        headers:{
            type:Array
        }
    }
}
</script>