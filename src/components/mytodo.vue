<template>
  <tbody>
      <!-- ここに <tr> で ToDo の要素を1行づつ繰り返し表示 -->
      <tr>
          <th>{{ item.id }}</th>
          <td>{{ item.comment }}</td>
          <td class="state">
              <!-- 状態変更ボタンのボタン -->
              <button>{{ item.state }}</button>
          </td>
          <td class="button">
              <!-- 削除ボタンのボタン -->
              <button>削除</button>
          </td>
      </tr>
  </tbody>
</template>

<script>
export default {

}
</script>

<style>

</style>