<template>
<div>
  <div v-for="blog in blogs" :key="blog">
      <v-card>
          <v-img :src="blog.img"></v-img>
          <h1>{{blog.title}}</h1>
          <h6>{{blog.subTitle}}</h6>
          <p>{{blog.caption}}</p>
          <em>{{blog.date}}</em>
      </v-card>
  </div>
</div>
</template>

<script>
export default {
    data () {
        return {
            blogs: [
                { title: 'First Blog', subTitle: 'Lorem ipsum dolor sit amet', caption: 'Lorem, ipsum dolor sit amet consectetur adipisicing elit. Et, impedit.', img: '/images/1.jpg', date: '01/12/1900'},
                { title: 'First Blog', subTitle: 'Lorem ipsum dolor sit amet', caption: 'Lorem, ipsum dolor sit amet consectetur adipisicing elit. Et, impedit.', img: '/images/2.jpg', date: '01/12/1900'},
                { title: 'First Blog', subTitle: 'Lorem ipsum dolor sit amet', caption: 'Lorem, ipsum dolor sit amet consectetur adipisicing elit. Et, impedit.', img: '/images/3.jpg', date: '01/12/1900'},
                { title: 'First Blog', subTitle: 'Lorem ipsum dolor sit amet', caption: 'Lorem, ipsum dolor sit amet consectetur adipisicing elit. Et, impedit.', img: '/images/4.jpg', date: '01/12/1900'},
                { title: 'First Blog', subTitle: 'Lorem ipsum dolor sit amet', caption: 'Lorem, ipsum dolor sit amet consectetur adipisicing elit. Et, impedit.', img: '/images/5.jpg', date: '01/12/1900'},
                { title: 'First Blog', subTitle: 'Lorem ipsum dolor sit amet', caption: 'Lorem, ipsum dolor sit amet consectetur adipisicing elit. Et, impedit.', img: '/images/6.jpg', date: '01/12/1900'},
                { title: 'First Blog', subTitle: 'Lorem ipsum dolor sit amet', caption: 'Lorem, ipsum dolor sit amet consectetur adipisicing elit. Et, impedit.', img: '/images/7.jpg', date: '01/12/1900'},
                { title: 'First Blog', subTitle: 'Lorem ipsum dolor sit amet', caption: 'Lorem, ipsum dolor sit amet consectetur adipisicing elit. Et, impedit.', img: '/images/8.jpg', date: '01/12/1900'},
                { title: 'First Blog', subTitle: 'Lorem ipsum dolor sit amet', caption: 'Lorem, ipsum dolor sit amet consectetur adipisicing elit. Et, impedit.', img: '/images/9.jpg', date: '01/12/1900'},
                { title: 'First Blog', subTitle: 'Lorem ipsum dolor sit amet', caption: 'Lorem, ipsum dolor sit amet consectetur adipisicing elit. Et, impedit.', img: '/images/10.jpg', date: '01/12/1900'},
                { title: 'First Blog', subTitle: 'Lorem ipsum dolor sit amet', caption: 'Lorem, ipsum dolor sit amet consectetur adipisicing elit. Et, impedit.', img: '/images/11.jpg', date: '01/12/1900'},
                
                
            ]
        }
    }
}
</script>

<style>

</style>