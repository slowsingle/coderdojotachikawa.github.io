---
layout: default
---

<div class="row">
    <div class="col-md-12">
    </div>
</div>
<div class="row">
    <div class="col-md-12">
    はじめての方はこちらをご確認ください。（準備中）
    </div>
</div>
<div class="row">
    <div class="col-md-12">
    <h4 style="background-color:#1169da; border-radius: 5px; color:#FFFFFF; padding:5px 0px 5px 10px;">
        開催予定
    </h4>
    </div>
    <div class="col-md-12" style="margin-bottom:10px;">
      ※参加お申し込みにはイベント管理サービス「connpass」のアカウント登録が必要です。<br/>
      各回の詳細な情報については、お申し込みページにてご確認ください。<br/>
    </div>
    <div class="col-md-6" style="margin-bottom: 10px;">
        <div class="card">
          <div class="card-body">
            <table class="table">
              <tbody>
                <tr>
                    <th scope="row">参加費</th>
                    <td>無料<br/>（会場で寄付金を募っています）</td>
                </tr>
                <tr>
                    <th scope="row">持ち物</th>
                    <td>ノートパソコン、またはiPadなど<br/>各自やりたいことを持参する</td>
                </tr>
                <tr id="infomation">
                  <th scope="row">開催の最新情報はこちらを参照してください。</th>
                  <td>
                    <a href="https://coderdojo-tachikawa.connpass.com/">https://coderdojo-tachikawa.connpass.com/</a>
                  </td>
                </tr>
              </tbody>
            </table>
          </div>
        </div>
    </div>
    <div class="col-md-6" style="margin-bottom: 10px;" id="to-table">
        <div class="card" id="first-card" style="display:none;">
            <div class="card-body">
            <h5 class="card-title" style="text-align:center; background-color:#FFAAAA; border-radius: 5px; padding:10px 0px 0px 10px;"><label id="to_eventTitle"></label></h5>
            <!-- イベント開催日 -->
            <table class="table">
                <tbody>
                <tr>
                    <th scope="row">日程</th>
                    <td><label id="to_eventYear"></label><label id="to_eventDate"></label></td>
                </tr>
                <tr>
                    <th scope="row">時間</th>
                    <td><label id="to_eventStime"></label>〜<label id="to_eventEtime"></label></td>
                </tr>
                <tr>
                    <th scope="row">会場</th>
                    <td><label id="to_eventPlace"></label></td>
                </tr>
                <tr>
                    <th scope="row">申込状況</th>
                    <td>
                    <label id="to_eventAccepted"></label>／<span id="to_eventLimit"></span>人
                    <br/>
                    キャンセル待ち：<label id="to_eventWaiting"></label>人
                    </td>
                </tr>
                <tr>
                    <td colspan="2" style="text-align:center;">
                    <!-- 申し込みボタン -->
                    <button type="button" class="btn btn-primary"  id="to_eventLink"><label id="to_enterBtn"></label></button>
                    </td>
                </tr>
                </tbody>
            </table>
            </div>
        </div>
    </div>
    <div class="col-md-6" id="nx-table">
        <div class="card" id="second-card" style="display:none;">
            <div class="card-body">
                <h5 class="card-title" style="text-align:center; background-color:#FFFF77; border-radius: 5px; padding:10px 0px 0px 10px;"><label id="nx_eventTitle"></label></h5>
                <!-- イベント開催日 -->
                <table class="table">
                    <tbody>
                    <tr>
                        <th scope="row">日程</th>
                        <td><label id="nx_eventYear"></label><label id="nx_eventDate"></label></td>
                    </tr>
                    <tr>
                        <th scope="row">時間</th>
                        <td><label id="nx_eventStime"></label>〜<label id="nx_eventEtime"></label></td>
                    </tr>
                    <tr>
                        <th scope="row">会場</th>
                        <td><label id="nx_eventPlace"></label></td>
                    </tr>
                    <tr>
                        <th scope="row">申込状況</th>
                        <td>
                        <label id="nx_eventAccepted"></label>／<span id="nx_eventLimit"></span>人
                        <br/>
                        キャンセル待ち：<label id="nx_eventWaiting"></label>人
                        </td>
                    </tr>
                    <tr>
                        <td colspan="2" style="text-align:center;">
                        <!-- 申し込みボタン -->
                        <button type="button" class="btn btn-primary"  id="nx_eventLink"><label id="nx_enterBtn"></label></button>
                        </td>
                    </tr>
                    </tbody>
                </table>
            </div>
        </div>
    </div>
    <div class="col-md-12">
        <iframe src="https://calendar.google.com/calendar/embed?title=CoderDojo%20%E7%AB%8B%E5%B7%9D%20%E3%82%B9%E3%82%B1%E3%82%B8%E3%83%A5%E3%83%BC%E3%83%AB&amp;mode=AGENDA&amp;height=600&amp;wkst=1&amp;hl=ja&amp;bgcolor=%23ffffff&amp;src=coderdojo.tachikawa%40gmail.com&amp;color=%2328754E&amp;ctz=Asia%2FTokyo" style="border-width:0; margin-top:20px;" width="100%" height="240" frameborder="0" scrolling="no"></iframe>
    </div>
</div>
