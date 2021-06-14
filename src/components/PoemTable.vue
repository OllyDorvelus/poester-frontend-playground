<template>
  <div id="poem-table">
    <v-container>
      <v-data-table
        :headers="headers"
        :items="poems"
        :items-per-page="5"
        class="elevation-1"
      ></v-data-table>
    </v-container>
  </div>
</template>

<script>
export default {
  name: "PoemTable",
  data() {
    return {
      headers: [
        {
          text: "Title",
          align: "start",
          sortable: false,
          value: "title",
        },
        { text: "Genre", value: "genre" },
        { text: "Actions", value: "action" },
      ],
      poems: [
        {
          _id: "60c6f2900207d88c6b64c6cc",
          title: "sample title2",
          genre: "sample genre2",
        },
        {
          _id: "60c6f290913f4045613aa71e",
          title: "sample title1",
          genre: "sample genre1",
        },
        {
          _id: "60c6f29002d1a45bfb46bd03",
          title: "sample title2",
          genre: "sample genre3",
        },
        {
          _id: "60c6f29098645d134d7f5bcc",
          title: "sample title3",
          genre: "sample genre2",
        },
        {
          _id: "60c6f290a0f6d75facb36193",
          title: "sample title2",
          genre: "sample genre3",
        },
        {
          _id: "60c6f290e467700be35096d4",
          title: "sample title3",
          genre: "sample genre2",
        },
        {
          _id: "60c6f290e0f7a569da1df729",
          title: "sample title3",
          genre: "sample genre3",
        },
        {
          _id: "60c6f290900931bd3d5f6aea",
          title: "sample title2",
          genre: "sample genre1",
        },
        {
          _id: "60c6f2900c574312eeca6c0c",
          title: "sample title3",
          genre: "sample genre2",
        },
        {
          _id: "60c6f290dc4884abd6548e2a",
          title: "sample title3",
          genre: "sample genre3",
        },
        {
          _id: "60c6f290b9282df24a93a0c1",
          title: "sample title1",
          genre: "sample genre2",
        },
        {
          _id: "60c6f29016a78bbcdb054199",
          title: "sample title1",
          genre: "sample genre2",
        },
        {
          _id: "60c6f290041d00167634dd63",
          title: "sample title2",
          genre: "sample genre1",
        },
      ],
    };
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss"></style>
