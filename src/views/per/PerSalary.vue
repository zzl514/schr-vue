<template>
  <div>
    <el-tabs v-model="activeName" type="card">
      <el-tab-pane label="员工目前薪资" name="salInfo">
      </el-tab-pane>

      <el-tab-pane label="员工调薪记录" name="salMv">
      </el-tab-pane>

    </el-tabs>
  </div>
</template>


<script>
export default {
  name: "PerSalary",
  data() {
    return {
      // 默认为哪个选项
      activeName: "salInfo"
    };
  },
  //生命周期 - 创建完成（访问当前this实例）
  created() {},
  //生命周期 - 挂载完成（访问DOM元素）
  mounted() {}
};
</script>
<style scoped>

</style>
