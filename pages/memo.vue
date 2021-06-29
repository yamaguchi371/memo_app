<template>
    <section class="container">
        <h1>Memo</h1>
        <table>
            <tr>
                <th>Title</th>
                <td><input type="text" name="title"
                class="title" size="40"
                v-model="title" @focus="set_flg">
                <button @click="find">find</button></td>
            </tr>
        </table>
    </section>
</template>