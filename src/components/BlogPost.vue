<template>
  <div id="blog-entry">
    <h1>This is a Lorem Ipsum Entry</h1>

    <markdown-it-vue :content="content" />
  </div>
</template>

<script>
import MarkItDownVue from "markdown-it-vue";

export default {
  name: "blog-post",
  components: {
    "markdown-it-vue": MarkItDownVue,
  },
  data() {
    return {
      title: "Test",
      content: `### This is some markdown

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus libero sapien, finibus at ipsum sit amet, pretium lobortis ex. Morbi consectetur quis neque nec iaculis. Proin quis enim semper, condimentum sapien sit amet, euismod augue. In semper leo ut orci tincidunt, a bibendum felis fringilla. Vivamus turpis nunc, vehicula quis hendrerit vitae, euismod non tellus. Curabitur iaculis turpis viverra nisi varius molestie. Nullam condimentum sollicitudin justo a varius. Vivamus faucibus eu nibh sed egestas. Nunc nec mi quis tortor egestas ultricies in at est. Sed interdum sem ac turpis bibendum, id dictum metus ultricies. Donec iaculis sem diam, ac accumsan nunc pellentesque eget. Mauris non neque lorem. Nunc maximus tempus justo sodales ornare. Phasellus vehicula nibh tortor, et sagittis neque pellentesque eget. Donec et consectetur enim.

Etiam mollis libero et auctor tristique. Praesent eget dolor ut orci convallis ultricies. Phasellus convallis eleifend enim vitae fermentum. Curabitur commodo risus sit amet nunc molestie imperdiet. Donec sit amet justo et mauris congue tempus id eget ligula. Nulla iaculis pharetra turpis. Sed leo tortor, placerat vel mattis non, aliquam nec libero. Nulla finibus est sit amet tellus iaculis, vel malesuada orci ultricies. Donec elementum consectetur massa eu euismod. Cras condimentum orci in augue consectetur, sed faucibus odio fringilla. Morbi pulvinar orci eget est laoreet, ut venenatis ligula auctor. Cras tempor arcu viverra sagittis tincidunt. In volutpat, elit quis efficitur blandit, massa ligula sodales massa, sit amet bibendum diam ante convallis urna. Nam eget cursus nunc. Donec commodo dapibus tempus. Integer aliquam blandit tellus nec rutrum.

Aliquam rhoncus venenatis nibh, at dictum odio elementum in. Nullam sapien lacus, auctor at consectetur a, aliquet rhoncus ex. Sed ultricies luctus ligula, eget ultrices diam sodales dictum. Duis eleifend ante ut nunc convallis, non volutpat lorem ornare. Nulla tincidunt ex ut mollis auctor. Mauris eu erat ac erat accumsan finibus. Ut posuere tempor sapien vulputate malesuada. Duis eget ante sit amet eros pulvinar commodo a ut erat. Vestibulum tempus tortor erat, sed efficitur lectus convallis sed. Aliquam eu est eu turpis condimentum lobortis. Integer quis mi in nisl efficitur pretium sit amet et quam. Sed ut leo ligula. Fusce at odio quis erat elementum egestas. Pellentesque ultrices diam felis, a ullamcorper nisi porttitor commodo. Donec a fringilla magna. Duis in lorem eu dui elementum rutrum sit amet eu justo.

Etiam eu ipsum at risus feugiat condimentum. Vestibulum euismod purus consequat enim auctor, id facilisis nunc egestas. Mauris auctor pellentesque diam. Morbi purus sem, molestie quis molestie sed, iaculis eget neque. Aenean vestibulum tempor arcu, et commodo augue. Phasellus laoreet nisl vitae est vehicula maximus. Proin vel feugiat est, non gravida ante. Integer sed rhoncus nisl, sit amet placerat ex. Curabitur vel tincidunt magna. Morbi elit felis, tristique vitae aliquam non, tincidunt nec elit. Pellentesque aliquet nunc ipsum, ac mollis sem scelerisque sed. Donec malesuada pharetra risus et venenatis. Morbi posuere dapibus pellentesque. Sed nec lobortis justo.

Sed imperdiet turpis quis vestibulum dignissim. Nulla feugiat convallis orci eu ullamcorper. Aenean ultrices, lectus eget consequat lacinia, quam augue posuere leo, sit amet placerat lectus leo a ligula. Mauris in felis sed purus vehicula euismod ac ut arcu. Maecenas faucibus sem nec sem egestas blandit a non massa. Curabitur a rhoncus enim. Morbi convallis dignissim feugiat. Pellentesque sodales egestas libero eget posuere. Integer id libero in mauris convallis suscipit. Aliquam dolor quam, mollis nec placerat eu, ultrices et eros. Pellentesque urna leo, interdum non turpis et, lacinia efficitur metus. Nulla in blandit ipsum. Vestibulum a metus vel orci ultricies consequat id sollicitudin augue. Nullam id pellentesque dolor, a bibendum mi. Duis aliquet leo diam, quis elementum diam dapibus quis. Proin tincidunt varius sem, semper congue massa dictum eget.`,
      more: "This",
    };
  },
};
</script>

<style></style>
