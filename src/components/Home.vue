<template>
  <el-row>
    <el-col :span="12">
      <el-card :body-style="{ padding: '0px' }">
        <div style="padding: 14px;">
          <span>Griller 1</span>
          <div class="bottom clearfix">
            <time class="time">Heute</time>
            <el-button type="text" class="button">{{btnLabel}}</el-button>
          </div>
        </div>
      </el-card>
    </el-col>
    <el-col :span="12">
      <el-card :body-style="{ padding: '0px' }">
        <div style="padding: 14px;">
          <span>Griller 2</span>
          <div class="bottom clearfix">
            <time class="time">Heute</time>
            <el-button type="text" class="button">{{btnLabel}}</el-button>
          </div>
        </div>
      </el-card>
    </el-col>
  </el-row>
</template>

<script>
export default {
  name: 'hello',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App',
      btnLabel: 'Ansehen'
    }
  }
}
</script>
