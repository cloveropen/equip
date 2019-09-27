<template>
  <v-app id="equip.cloveropen.com">
    <Basepage />
    <v-container fluid>
      <v-layout justify-start>
        <v-row>
          <v-col cols="12">
            <v-hover
              v-slot:default="{ hover }"
              open-delay="100"
              close-delay="150"
            >
              <v-card :elevation="hover ? 18 : 0" class="mx-auto">
                <v-card-title>设备基础数据</v-card-title>
                <v-card-actions>
                  <v-btn class="ma-3" rounded color="success" x-large dark
                    ><v-icon left>mdi-pencil</v-icon> 科室管理</v-btn
                  >
                  <v-btn class="ma-3" rounded color="success" x-large dark>
                    <v-icon left>mdi-pencil</v-icon> 人员管理</v-btn
                  >
                  <v-btn class="ma-3" rounded color="success" x-large dark>
                    <v-icon left>mdi-pencil</v-icon> 期间划分调整</v-btn
                  >
                  <v-btn class="ma-3" rounded color="success" x-large dark>
                    <v-icon left>mdi-pencil</v-icon>设备供应商管理</v-btn
                  >
                  <v-btn class="ma-3" rounded color="success" x-large dark>
                    <v-icon left>mdi-pencil</v-icon> 设备目录管理</v-btn
                  >
                  <v-btn class="ma-3" rounded color="success" x-large dark>
                    <v-icon left>mdi-pencil</v-icon> 设备使用状态</v-btn
                  >
                  <v-btn class="ma-3" rounded color="success" x-large dark>
                    <v-icon left>mdi-pencil</v-icon> 设备入出分类</v-btn
                  >
                </v-card-actions>
              </v-card>
            </v-hover>
          </v-col>

          <v-col cols="4">
            <v-hover
              v-slot:default="{ hover }"
              open-delay="100"
              close-delay="150"
            >
              <v-card :elevation="hover ? 18 : 0" class="mx-auto">
                <v-card-title>设备采购计划</v-card-title>
                <v-card-actions>
                  <v-btn class="ma-3" rounded color="primary" x-large dark
                    ><v-icon left>mdi-pencil</v-icon> 设备购买申请</v-btn
                  >
                  <v-btn class="ma-3" rounded color="primary" x-large dark>
                    <v-icon left>mdi-pencil</v-icon> 设备采购计划</v-btn
                  >
                  <v-spacer>&emsp;</v-spacer><v-spacer>&emsp;</v-spacer>
                </v-card-actions>
              </v-card>
            </v-hover>
          </v-col>

          <v-col cols="12">
            <v-hover
              v-slot:default="{ hover }"
              open-delay="100"
              close-delay="150"
            >
              <v-card :elevation="hover ? 18 : 0" class="mx-auto">
                <v-card-title>设备库房管理</v-card-title>
                <v-card-actions>
                  <v-btn class="ma-3" rounded color="secondary" x-large dark
                    ><v-icon left>mdi-pencil</v-icon> 采购入库</v-btn
                  >
                  <v-btn class="ma-3" rounded color="secondary" x-large dark>
                    <v-icon left>mdi-pencil</v-icon> 其他入库</v-btn
                  >
                  <v-btn class="ma-3" rounded color="secondary" x-large dark>
                    <v-icon left>mdi-pencil</v-icon> 设备调拨</v-btn
                  >
                  <v-btn class="ma-3" rounded color="secondary" x-large dark>
                    <v-icon left>mdi-pencil</v-icon>领用管理</v-btn
                  >
                  <v-btn class="ma-3" rounded color="secondary" x-large dark>
                    <v-icon left>mdi-pencil</v-icon> 其他出库</v-btn
                  >
                  <v-btn class="ma-3" rounded color="secondary" x-large dark>
                    <v-icon left>mdi-pencil</v-icon> 设备盘存</v-btn
                  >
                  <v-btn class="ma-3" rounded color="secondary" x-large dark>
                    <v-icon left>mdi-pencil</v-icon> 设备卡片</v-btn
                  >
                </v-card-actions>
              </v-card>
            </v-hover>            
          </v-col>

          <v-col cols="12">
            <v-hover
              v-slot:default="{ hover }"
              open-delay="100"
              close-delay="150"
            >
              <v-card :elevation="hover ? 18 : 0" class="mx-auto">
                <v-card-title>在用设备管理</v-card-title>
                <v-card-actions>
                  <v-btn class="ma-3" rounded color="warning" x-large dark
                    ><v-icon left>mdi-pencil</v-icon>设备使用</v-btn
                  >
                  <v-btn class="ma-3" rounded color="warning" x-large dark>
                    <v-icon left>mdi-pencil</v-icon>设备保养</v-btn
                  >
                  <v-btn class="ma-3" rounded color="warning" x-large dark>
                    <v-icon left>mdi-pencil</v-icon>设备检查</v-btn
                  >
                  <v-btn class="ma-3" rounded color="warning" x-large dark>
                    <v-icon left>mdi-pencil</v-icon>设备维修</v-btn
                  >
                  <v-btn class="ma-3" rounded color="warning" x-large dark>
                    <v-icon left>mdi-pencil</v-icon>设备变动</v-btn
                  >
                  <v-btn class="ma-3" rounded color="warning" x-large dark>
                    <v-icon left>mdi-pencil</v-icon>设备折旧</v-btn
                  >
                  <v-btn class="ma-3" rounded color="warning" x-large dark>
                    <v-icon left>mdi-pencil</v-icon>设备下帐</v-btn
                  >
                </v-card-actions>
              </v-card>
            </v-hover>            
          </v-col>

          <v-col cols="12">
            <v-hover
              v-slot:default="{ hover }"
              open-delay="100"
              close-delay="150"
            >
              <v-card :elevation="hover ? 18 : 0" class="mx-auto">
                <v-card-title>查询与分析</v-card-title>
                <v-card-actions>
                  <v-btn class="ma-3" rounded color="success" x-large dark
                    ><v-icon left>mdi-pencil</v-icon>库存查询</v-btn
                  >
                  <v-btn class="ma-3" rounded color="success" x-large dark>
                    <v-icon left>mdi-pencil</v-icon>设备明细账</v-btn
                  >
                  <v-btn class="ma-3" rounded color="success" x-large dark>
                    <v-icon left>mdi-pencil</v-icon>入出汇总</v-btn
                  >
                  <v-btn class="ma-3" rounded color="success" x-large dark>
                    <v-icon left>mdi-pencil</v-icon>领用汇总</v-btn
                  >
                  <v-btn class="ma-3" rounded color="success" x-large dark>
                    <v-icon left>mdi-pencil</v-icon>分类帐</v-btn
                  >
                  <v-btn class="ma-3" rounded color="success" x-large dark>
                    <v-icon left>mdi-pencil</v-icon>设备折旧</v-btn
                  >
                  <v-btn class="ma-3" rounded color="success" x-large dark>
                    <v-icon left>mdi-pencil</v-icon>价值构成状况表</v-btn
                  >
                  <v-btn class="ma-3" rounded color="success" x-large dark>
                    <v-icon left>mdi-pencil</v-icon>质量状况表</v-btn
                  >
                  <v-btn class="ma-3" rounded color="success" x-large dark>
                    <v-icon left>mdi-pencil</v-icon>设备类别状况表</v-btn
                  >
                  <v-btn class="ma-3" rounded color="success" x-large dark>
                    <v-icon left>mdi-pencil</v-icon>设备分布状况表</v-btn
                  >
                  <v-btn class="ma-3" rounded color="success" x-large dark>
                    <v-icon left>mdi-pencil</v-icon>设备增减变动表</v-btn
                  >
                  <v-btn class="ma-3" rounded color="success" x-large dark>
                    <v-icon left>mdi-pencil</v-icon>医疗设备效益分析</v-btn
                  >
                  <v-btn class="ma-3" rounded color="success" x-large dark>
                    <v-icon left>mdi-pencil</v-icon>设备明细表</v-btn
                  >
                  <v-btn class="ma-3" rounded color="success" x-large dark>
                    <v-icon left>mdi-pencil</v-icon>设备领用明细表</v-btn
                  >
                  <v-btn class="ma-3" rounded color="success" x-large dark>
                    <v-icon left>mdi-pencil</v-icon>维修统计表</v-btn
                  >
                </v-card-actions>
              </v-card>
            </v-hover>            
          </v-col>

<v-col cols="4">
            <v-hover
              v-slot:default="{ hover }"
              open-delay="100"
              close-delay="150"
            >
              <v-card :elevation="hover ? 18 : 0" class="mx-auto">
                <v-card-title>设备系统管理</v-card-title>
                <v-card-actions>
                  <v-btn class="ma-3" rounded color="primary" x-large dark
                    ><v-icon left>mdi-pencil</v-icon>参数设置</v-btn
                  >
                  <v-btn class="ma-3" rounded color="primary" x-large dark>
                    <v-icon left>mdi-pencil</v-icon>设备月结管理</v-btn
                  >
                  <v-spacer>&emsp;</v-spacer><v-spacer>&emsp;</v-spacer>
                </v-card-actions>
              </v-card>
            </v-hover>
          </v-col>

        </v-row>
      </v-layout>
    </v-container>
  </v-app>
</template>

<script>
import Basepage from "../components/Basepage";
export default {
  components: {
    Basepage
  }
};
</script>
