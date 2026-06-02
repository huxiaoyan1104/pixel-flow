# 数据安全提醒

Pixel Flow 的收藏记录、下载历史和部分分析缓存保存在浏览器本地。执行清理、卸载扩展、清除浏览器扩展数据或重置浏览器配置前，请先导出备份。

<div class="docs-alert docs-alert-critical">
  <strong>高风险操作：请先备份</strong>
  <p>下面两项可能清空 Pixel Flow 的本地数据库。完成备份前，不建议继续操作。</p>
</div>

<table class="docs-risk-table">
  <thead>
    <tr>
      <th>操作</th>
      <th>是否会影响本地数据</th>
      <th>影响范围</th>
      <th>是否可恢复</th>
      <th>建议</th>
    </tr>
  </thead>
  <tbody>
    <tr class="risk-critical">
      <td><strong>卸载 Chrome 扩展</strong></td>
      <td>会</td>
      <td>Chrome 可能清空扩展本地数据库</td>
      <td>仅备份后可恢复</td>
      <td><strong>卸载前必须导出备份</strong></td>
    </tr>
    <tr class="risk-critical">
      <td><strong>清除浏览器扩展数据 / 重置浏览器配置</strong></td>
      <td>可能会</td>
      <td>可能清空 Pixel Flow 的本地数据库和设置</td>
      <td>取决于是否有备份</td>
      <td><strong>操作前导出备份</strong></td>
    </tr>
    <tr>
      <td>设置页清理下载历史</td>
      <td>会</td>
      <td>删除指定时间范围或全部下载历史记录</td>
      <td>仅备份后可恢复</td>
      <td>清理前先导出备份</td>
    </tr>
    <tr>
      <td>设置页清理收藏记录</td>
      <td>会</td>
      <td>删除指定时间范围或全部收藏记录及本地保存的图片数据</td>
      <td>仅备份后可恢复</td>
      <td>重要素材先导出备份</td>
    </tr>
    <tr>
      <td>删除自定义标签</td>
      <td>会部分影响</td>
      <td>删除标签定义，并从已收藏图片上移除该标签</td>
      <td>需要重新创建或导入备份</td>
      <td>删除前确认标签不再需要</td>
    </tr>
    <tr>
      <td>导入备份</td>
      <td>不会清空现有收藏</td>
      <td>合并收藏、下载历史和标签；偏好设置可能按备份恢复</td>
      <td>可继续调整设置</td>
      <td>确认备份属于当前账号</td>
    </tr>
    <tr>
      <td>退出登录 / 解绑账号</td>
      <td>通常不会清空本地数据</td>
      <td>影响账号状态、PRO 权限或绑定方式</td>
      <td>重新登录或重新绑定</td>
      <td>仍建议定期备份</td>
    </tr>
  </tbody>
</table>

## 如何备份

打开 Pixel Flow 侧边栏，进入「设置」→「数据备份与迁移」→「数据备份」，导出备份包并保存到你能找到的位置。

## 操作前检查

1. 是否已经导出最新备份。
2. 是否能找到刚导出的备份文件。
3. 是否确认当前操作会影响浏览器扩展数据。
4. 如果是卸载或重置浏览器配置，完成备份后再继续。
