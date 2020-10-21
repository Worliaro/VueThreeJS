<template>
  <el-row>
    <el-col :span="24">
      <div class="">
          <el-input v-model="input" placeholder="请输入内容"></el-input>
      </div>
    </el-col>
  </el-row>
</template>

<script>
export default {
  name: "Demo1",
  components: {},
  data() {
     return {
        input: ''
     }
  },
  mounted() {},
  methods: {}
};
</script>
