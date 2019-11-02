---
layout: default
---

<div class="container">
    <div class="row">
        <div class="col-md-12">
            <h4 style="background-color:#1169da; border-radius: 5px; color:#FFFFFF; padding:5px 0px 5px 10px;">
                開催予定
            </h4>
            <p>
                参加お申し込みにはイベント管理サービス「connpass」のアカウント登録が必要です。<br/>
                <a href="https://connpass.com/"><img src="/assets/images/connpass_logo_1.png" style="max-width: 180px;"></a><br/>
                各回の詳細な情報については、お申し込みページにてご確認ください。<br/>
                また、connpass内の<a href="https://coderdojo-tachikawa.connpass.com/">CoderDojo 立川グループ</a>のメンバーになっていただくことで、イベントの募集案内やお知らせをメールで受け取ることができます。
            </p>
        </div>
     </div>
     <div class="row">
        <div class="col-md-6" style="margin-bottom: 10px;">
            <div class="card">
              <div class="card-body">
                    <a href="https://coderdojo-tachikawa.connpass.com/"><img src="/assets/images/event_theme.png" class="img-fluid mb-4"></a>
                <table class="table">
                  <tbody>
                    <tr>
                        <th scope="row" style="width: 80px;">参加費</th>
                        <td>無料<br/>※会場で寄付金を募っています。</td>
                    </tr>
                    <tr>
                        <th scope="row">持ち物</th>
                        <td>ノートパソコン、またはiPadなど<br/>各自やりたいことを持参する</td>
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
        <div class="col-md-6">
            <div class="card" id="second-card">
                <div class="card-body">
                    <h5 class="card-title" style="background-color:#1169da; border-radius: 5px; color:#FFFFFF; padding:5px 0px 5px 10px;">
                        今後の開催スケジュール
                    </h5>
                    <p class="pb-2">
                        ※お申し込みは約一ヶ月前より可能となります。<br/>
                    </p>
                    <iframe src="https://calendar.google.com/calendar/embed?title=CoderDojo%20%E7%AB%8B%E5%B7%9D%20%E3%82%B9%E3%82%B1%E3%82%B8%E3%83%A5%E3%83%BC%E3%83%AB&amp;mode=AGENDA&amp;height=600&amp;wkst=1&amp;hl=ja&amp;bgcolor=%23ffffff&amp;src=coderdojo.tachikawa%40gmail.com&amp;color=%2328754E&amp;ctz=Asia%2FTokyo" style="border-width:0;" width="100%" height="280" frameborder="0" scrolling="no"></iframe>
                </div>
            </div>
        </div>
    </div>
    <div class="row">
        <div class="col-md-12">
            <h4 style="background-color:#1169da; border-radius: 5px; color:#FFFFFF; padding:5px 0px 5px 10px;">
                近日開催の他の道場を探す
            </h4>
            <p>
                立川以外のCoderDojoがたくさんあります。近日開催予定の道場をまとめたページがありますので、いろんな道場に参加してみてください。<br/>
                <a href="https://coderdojo.jp/events">https://coderdojo.jp/events</a>
            </p>
        </div>
    </div>
</div>
