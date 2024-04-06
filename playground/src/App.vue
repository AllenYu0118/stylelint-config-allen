<script setup lang="ts">
console.log('App.vue')
</script>

<template>
  <h1>Playground</h1>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  font-weight: bold;
  transition: filter 300ms;
  will-change: filter;
}

.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}

.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>

<style lang="scss" scoped>
.main {
  display: flex;
  width: 1200px;
  margin: 12px auto;
}

.main-right {
  flex: 1;
  padding: 16px 16px 32px;
  margin-left: 10px;
  background-color: #fff;
  border-radius: 8px;
  box-shadow: 0 2px 12px -4px rgb(0 0 0 / 12%);

  :deep() {
    .ant-table .ant-table-thead > tr > th {
      font-weight: normal;
    }

    .ant-table-small .ant-table-selection-column {
      width: 26px;
      min-width: 26px;
    }

    .ant-table.ant-table-small .ant-table-thead > tr > th {
      padding: 5px;
    }

    .ant-table.ant-table-small .ant-table-tbody tr > td {
      padding: 20px 5px;
    }

    .table-package-business,
    .table-package-residence,
    .table-open {
      .ant-table-tbody tr > td label.ant-checkbox-wrapper {
        margin-top: 20px;
      }
    }

    .header-effect {
      text-indent: 18px;
    }

    .ant-tabs-tab + .ant-tabs-tab {
      margin-left: 28px;
    }

    .ant-tabs-top > .ant-tabs-nav {
      margin-bottom: 5px;
    }

    .ant-tabs-small > .ant-tabs-nav .ant-tabs-tab {
      min-width: 85px;
    }
  }

  &.ware-open {
    padding: 0;
    background-color: unset;
    border-radius: unset;
    box-shadow: unset;
  }

  &.ware-recommend-effect {
    padding: 0;
    background-color: unset;
    border-radius: unset;
    box-shadow: unset;
  }
}
</style>

