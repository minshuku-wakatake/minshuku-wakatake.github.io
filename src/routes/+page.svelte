<script>
  import logo from "$lib/assets/logo.png";
  import ogpImage from "$lib/assets/ogp.png";

  const page = {
    title: "尻宿ワカタケ",
    authorXId: "@froggie3_",
    description: "Feederチャット「尻宿ワカタケ」の利用ルールです。",
    pictureDescription: {
      en: `A nicely drawn picture of Hatsune Miku, \
standing only with twintails symbolizing the sense of the chat crews' humor.`,
      ja: `ツインテールだけで立っている初音ミクの素敵な絵は、\
チャットクルーのユーモアのセンスを象徴しています。`,
    },
  };
</script>

<svelte:head>
  <meta name="description" content={page.description} />
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:creator" content={page.authorXId} />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <meta property="og:description" content={page.description} />
  <meta property="og:image" content={ogpImage} />
  <meta property="og:image:alt" content={page.pictureDescription.en} />
  <meta property="og:site_name" content={page.title} />
  <meta property="og:title" content={page.title} />
  <meta property="og:type" content="website" />
  <title>{page.title}</title>
  <link rel="apple-touch-icon" href={logo} />
  <link rel="icon" href={logo} type="image/png" />
</svelte:head>

<header class="container">
  <hgroup>
    <h1>Welcome to Wakatake shopping street!</h1>
  </hgroup>
</header>

<main class="container">
  <p>
    このページは<a target="_blank" href="https://www.x-feeder.info/">Feeder</a
    >チャット「<a
      target="_blank"
      href="https://www2.x-feeder.info/Kocchi_Minna/">尻宿ワカタケ</a
    >」向けのページです。
  </p>

  <h2>利用ルール</h2>
  <p>チャットはユーザー同士の交流を通して楽しむための場所です。</p>
  <ul>
    <li>
      管理人が不適切だと認識した行為・行動、またそれを行ったユーザーは予告なしに規制させていただく場合が御座いますので予めご了承ください。
      <br />
      またそういった不適切な行為・行動の早期発見のため、何かありましたら管理人まで個別メッセージでお知らせください。
    </li>
    <li>
      ここのチャットのユーザーの年齢層は小学生～成人までと非常に広いです。<br />
      目上の人間に対して必ずしも敬意を示す必要はありませんが、相手を思いやる心は弁えましょう。
    </li>
    <li>人として最低限の道徳は弁えてください。</li>
    <li>性的な話は控えていただくようお願いいたします。</li>
    <li>ここはチャット場ですので、挨拶は心がけることを推奨します。</li>
    <li>他人を自分の観念だけで否定するのはやめてください。</li>
    <li>意図的なNGワード回避はやめてください。</li>
    <li>公序良俗に反する行動などは規制させていただく場合がございます。</li>
  </ul>

  <h2>規制対象となる行為</h2>
  <p>以下の行為は規制対象になりますのでご遠慮ください。</p>
  <ul>
    <li>
      執拗な宣伝行為（会話するつもりがないと見なされるもの）。
      <ul>
        <li>ぶっちゃけこんな所で宣伝を行っても集まらないと思いますよ。</li>
      </ul>
    </li>
    <li>
      荒らし、またはそれに準ずるもの。
      <ul>
        <li>過度の荒らし行為は発見次第、即規制させていただきます。</li>
      </ul>
    </li>
    <li>
      執拗に長い論争・喧嘩・揉めごと。
      <ul>
        <li>
          ここはチャット場であり論争等をする場所ではありません。<br />
          ※無視機能を使えば一時的に無視する事は可能です。
        </li>
      </ul>
    </li>
    <li>
      嫌がらせ行為
      <ul>
        <li>
          ネタ程度のものなら許容範囲のうちですが過度なものはお控えください。<br
          />
          ※もし嫌がらせ行為を受け、嫌だと感じている場合は管理人に個別メッセージを送ってください。
        </li>
      </ul>
    </li>
    <li>
      アダルト・18禁内容の投稿・宣伝等 <br />
      ※グロ・エロ画像を貼る行為<br />
      ※個別メッセージで「生放送やって」や「パンツ見せて」等の発言
      <ul>
        <li>Feederチャットはアダルト目的での使用は禁止されています。</li>
      </ul>
    </li>
  </ul>

  <h2>その他</h2>
  <figure>
    <a target="_blank" href={ogpImage}
      ><img
        style="width: 100%"
        decoding="async"
        src={ogpImage}
        alt={page.pictureDescription.en}
      /></a
    >
    <figcaption>{page.pictureDescription.ja}</figcaption>
  </figure>

  <p>
    チャットを利用する際に成り済ましを防ぐため、トリップを付けることを推奨します。<br
    />
    （トリップの付け方は<a
      target="_blank"
      href="https://www.x-feeder.info/usages/trip/">トリップを使用する</a
    >を参照。）
  </p>
  <p>※動画・投稿ファイルは一定の量で自動削除されるので予めご了承ください。</p>
  <p>
    チャットルームの相互リンクを受け付けています。<br />
    相互を希望する場合は管理人に声をかけてください。
  </p>
  <p>↓Feederチャットの利用規約も併せて読むようお願いします。</p>
  <p>
    <a target="_blank" href="https://www.x-feeder.info/terms_of_use.php"
      >https://www.x-feeder.info/terms_of_use.php</a
    >
  </p>
</main>

<style>
  @import "simpledotcss/simple.min";
  ul {
    padding-left: 1em;
  }
  li {
    margin: 1em auto;
  }
</style>
