<template>
  <v-app dark>
    <v-container fill-height class="pa-2">
      <v-layout align-center justify-center>
        <v-flex lg8 md10 sm11 xs12>
          <v-img
            app
            :src="require(`@/assets/header-img.png`)"
            height="25vh"
          >
            <v-layout 
              pa-2 column fill-height class="lightbox white--text" 
              justify-center align-center
            >
              <v-spacer></v-spacer>
              <v-flex>
                <div class="comfortaa text-xs-center" id="subheader">
                  Photography by
                </div>
                <div class="pacifico text-xs-center" id="header">
                  Anke Marsolin
                </div>
              </v-flex>
            </v-layout>
          </v-img>
          <v-toolbar class="sticky" app>
            <v-toolbar-title class="pacifico">
              <v-icon class="pb-1">camera_alt</v-icon>
              A. Marsolin
            </v-toolbar-title>
            <v-spacer></v-spacer>
            <v-toolbar-items class="hidden-xs-only">
              <v-btn flat>
                <v-icon>home</v-icon>
                Home
              </v-btn>
              <v-btn flat>
                <v-icon>photo_library</v-icon>
                Portfolio
              </v-btn>
              <v-btn flat>
                <v-icon>message</v-icon>
                Kontakt
              </v-btn>
            </v-toolbar-items>
          </v-toolbar>
        
          <v-content class="pa-0">
            <Carousel />
            <div>
              <p>
                <span>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Aut nemo, dolore enim quo, reiciendis facere necessitatibus ipsa tempore et sunt magnam vero saepe voluptatem tenetur eaque praesentium iusto veniam! Amet?</span>
                <span>In velit ullam, vero enim at quam cupiditate eaque quis minima, laudantium quod pariatur, sequi consequuntur nulla voluptatum culpa cumque? Vel qui nostrum in consequatur quas, tempore iure atque quo?</span>
                <span>Dicta quidem at hic? Libero, commodi distinctio dignissimos omnis odio quibusdam, amet molestiae eveniet magnam corrupti explicabo iste necessitatibus possimus velit! Culpa tempora dignissimos magni tenetur, iure itaque excepturi ullam!</span>
                <span>Quod iste, voluptate aut obcaecati, maxime repellat tenetur cupiditate sit a reiciendis nihil amet illum similique laudantium expedita omnis. Porro dolores molestiae consequatur distinctio ex architecto voluptas illo neque facere!</span>
                <span>Molestiae reprehenderit enim natus, reiciendis sed unde quidem cumque illo incidunt molestias asperiores voluptate odio ad eos vitae corporis praesentium facere qui? Amet nesciunt voluptates pariatur sed cum repellat nisi.</span>
                <span>Debitis, praesentium id eos accusamus necessitatibus dolorem doloribus deleniti cumque quis adipisci numquam rem, dolorum unde qui ut perferendis nemo vitae et architecto fugit pariatur maxime, quasi similique distinctio! Ducimus!</span>
                <span>Maiores sapiente facilis, dicta mollitia tempore neque dignissimos, magni iste corporis autem quod possimus omnis perferendis non deserunt. Unde eaque architecto dignissimos, possimus qui nobis molestiae saepe quas impedit sit.</span>
                <span>Repellat similique vel tempore voluptates minus possimus aliquam! Ipsam enim modi animi sed. Assumenda quam veritatis illum, velit quibusdam perferendis aliquid pariatur sequi magni unde adipisci iure sint recusandae officiis?</span>
                <span>Excepturi aspernatur minus provident aliquam accusantium sit eos corrupti nam a eveniet nostrum necessitatibus distinctio repellendus soluta ipsum, aperiam non quo? Provident repellat quasi voluptatibus fugiat aperiam officiis itaque ea.</span>
                <span>Voluptatum veniam beatae quod facere similique necessitatibus, nostrum maiores at ab sequi deleniti qui doloremque laboriosam laborum. Aut nesciunt vel eum dignissimos, sit sunt nihil amet molestias fuga quae cumque!</span>
                <span>Dicta odio illum sapiente nulla labore debitis rem fugit repudiandae accusamus fuga! Optio animi eaque, molestiae itaque laboriosam dolore modi voluptate praesentium reprehenderit impedit incidunt provident magnam, nulla saepe! Dolor?</span>
                <span>Maiores, aut? Quasi labore maxime aperiam debitis autem commodi itaque facere accusamus quam placeat nihil porro alias rerum, aspernatur illo asperiores eius natus, aliquam, perferendis maiores ex. Animi, fuga ipsum?</span>
                <span>Vero officiis magnam corrupti quis placeat sit eligendi magni fugiat minus est libero perferendis ex distinctio amet quidem optio quisquam pariatur ipsum veniam, reprehenderit quibusdam recusandae molestias nisi. Culpa, quos.</span>
                <span>Alias illum reiciendis eum recusandae voluptatem fugit accusamus earum numquam culpa dolore, vitae totam! Autem reprehenderit qui, at, neque dignissimos iste aliquid unde dicta soluta sint reiciendis nam optio exercitationem.</span>
                <span>Nesciunt blanditiis debitis commodi nulla soluta repellat animi praesentium officia eveniet sint atque obcaecati similique ipsum, neque, reiciendis nam corrupti modi suscipit architecto! Repellendus porro animi non doloribus sit quidem.</span>
                <span>Similique vel amet hic ipsum, tempora, odit laboriosam atque exercitationem fugit accusantium maiores deleniti aperiam modi. Commodi quidem eligendi assumenda. Nostrum illo velit reiciendis voluptatibus sint eaque saepe quod dicta?</span>
                <span>Tempore commodi velit architecto est corrupti. Sequi nisi, voluptas nulla quibusdam ea aliquam cupiditate ab animi nesciunt nostrum quis iusto esse quos minus cumque, expedita, fugit officiis! Iusto, laborum ducimus?</span>
                <span>Quas, distinctio ipsum, doloremque ea, culpa tempora possimus deserunt corrupti voluptates voluptatem obcaecati ab et dicta aut illo ipsa molestias cum minus qui ducimus magni magnam! Impedit enim dignissimos beatae?</span>
                <span>Ut dolores quisquam veritatis sapiente perferendis quidem! Incidunt nihil ad voluptates officia velit rem quas. Optio numquam dolore nisi totam, ipsam nihil aliquid. Ratione rerum enim laboriosam recusandae, nobis quae.</span>
                <span>Ad similique corrupti natus laboriosam, sint libero consequuntur ducimus ut? Tenetur fugiat omnis itaque repellat rem recusandae expedita repudiandae provident maiores, doloribus ullam consequatur distinctio veritatis perferendis corrupti, iste officiis!</span>
                <span>Labore ratione iure itaque, sapiente velit dolorem officiis laudantium amet odit ipsa veniam ipsam consequuntur pariatur, earum cupiditate aliquam illum provident animi! Voluptatem pariatur laborum saepe itaque perspiciatis nesciunt maxime?</span>
                <span>Fugit neque odit sequi modi mollitia enim maxime voluptas est fuga quisquam, expedita laudantium! Sunt ut, error amet cumque delectus nihil obcaecati consequatur beatae eos quam alias omnis ea iusto.</span>
                <span>Doloremque recusandae, atque facere explicabo maxime minus iusto assumenda laudantium ea sit dolorem, laborum voluptatem deserunt repellat hic corporis placeat. Dicta, earum fugit. Non alias cumque est iure! Provident, beatae?</span>
                <span>Eius sapiente labore similique praesentium mollitia voluptatum eos, iste voluptates unde cumque nostrum reprehenderit aliquid, voluptatem accusamus sunt quis? Nulla, earum! Iste quaerat corrupti distinctio adipisci alias labore repellendus eos?</span>
                <span>Adipisci praesentium odit nobis architecto recusandae veritatis, libero deserunt fugiat mollitia optio officia voluptatem accusantium voluptates eveniet dolorum impedit natus nisi atque repellendus, neque aliquam alias inventore quas. Alias, dolorum.</span>
                <span>Quibusdam dolor libero molestias quis, optio reprehenderit laborum aut sequi inventore molestiae expedita dolores magnam natus, harum, vero deleniti at tenetur eveniet delectus! Quisquam provident facilis fugit quam, repellendus laudantium?</span>
                <span>Unde explicabo fugiat cupiditate pariatur hic exercitationem expedita, officiis voluptatum itaque ipsam! Nam maxime ex id quos nesciunt voluptatibus, fugit ab. Delectus nemo eaque quibusdam, facilis beatae dolor animi nisi?</span>
                <span>Iste repellendus, fugiat reprehenderit consectetur accusantium ex at, perspiciatis doloremque nisi exercitationem dolor non nesciunt totam laudantium nemo? Temporibus, magnam. Aliquam iusto voluptatem rem corrupti nisi, debitis ipsum laboriosam autem.</span>
                <span>Tenetur perspiciatis veniam possimus cupiditate ullam vero officiis fugiat numquam quas. Iusto, corporis. Officia laudantium modi similique, optio dolor impedit totam minus temporibus vitae. Inventore placeat iusto repudiandae sunt debitis?</span>
                <span>Amet aliquam consequatur odio architecto quisquam adipisci, praesentium ad error ea dolores, nemo recusandae aspernatur temporibus ullam nostrum perspiciatis assumenda vero asperiores! Inventore incidunt tenetur veritatis amet quaerat ut blanditiis!</span>
                <span>Dolor quia nesciunt sapiente aperiam enim, facilis consequatur quas expedita, animi, placeat facere non corrupti ducimus rerum odio esse optio repellat doloribus quibusdam. Ab architecto corporis mollitia sunt possimus maxime?</span>
                <span>Repellat et possimus debitis officia, animi est obcaecati iste molestias enim accusantium tempora, aut impedit consequuntur repellendus itaque illo harum commodi sequi cum. Error exercitationem ratione suscipit? Maxime, voluptatibus doloribus.</span>
                <span>Id rerum est laboriosam deserunt pariatur possimus illo? Ad ea deleniti, libero dolor dolorum perspiciatis laboriosam, maiores dolores dolorem corrupti facere amet ullam dicta non, iure iusto quaerat hic nihil?</span>
                <span>Voluptate, officiis omnis consequatur dolorum labore possimus maiores error tempore neque ratione eaque, inventore laborum ad, ducimus facilis harum maxime ipsum veniam esse quia? Ea numquam accusamus quas rem at.</span>
                <span>Veritatis autem voluptatem facere quis quasi voluptatum quas, nostrum deserunt, quo voluptates, neque mollitia harum laudantium ut magni odit expedita reiciendis modi quidem libero! Illo non delectus modi laudantium dicta.</span>
                <span>Illum animi, dignissimos sequi doloribus aspernatur illo, molestias quam eius provident ducimus sit veritatis voluptas corrupti tempore neque deserunt qui voluptate beatae nulla aliquam deleniti. Doloremque laborum mollitia harum fugiat!</span>
                <span>Aliquid accusantium repellendus recusandae officiis odio veritatis molestias numquam architecto eius nulla. Numquam rerum, nemo corrupti in modi velit quo cupiditate blanditiis alias nostrum magni quod ipsa ab voluptatibus hic.</span>
                <span>Officiis nostrum eveniet voluptas a id aliquid sunt cum rerum at asperiores, consequatur voluptatum est fugiat animi totam, praesentium nemo, laborum nobis molestiae iusto quae? Accusantium, officiis! Placeat, nam earum.</span>
                <span>Quam placeat excepturi officiis id sunt necessitatibus modi nobis iste architecto ullam dolorem porro animi quia, eveniet eius ducimus quisquam quidem molestiae alias? Odit beatae, consectetur tempora incidunt blanditiis sint.</span>
                <span>A cum nihil voluptatem praesentium nemo eius iure magni inventore, laboriosam ullam delectus nesciunt! Quisquam soluta minima exercitationem, delectus error doloremque natus! Ipsam animi iste atque eligendi inventore non natus?</span>
                <span>Necessitatibus nisi eum nobis! Soluta reprehenderit doloribus neque? Repellat perferendis expedita dolore temporibus commodi, minus possimus esse nostrum quam nesciunt, sit rerum provident dignissimos placeat quisquam voluptatem. Tempora, minus quae!</span>
                <span>Illum quasi quas molestias voluptas ut reiciendis amet, animi eius modi sit consequatur autem harum nemo repellat voluptatibus magnam doloribus, esse totam ea consectetur soluta laborum eaque aspernatur! Iste, neque.</span>
                <span>Delectus fugiat eligendi dignissimos optio suscipit, consequuntur harum! Id possimus assumenda sint voluptates, magni aliquam perspiciatis architecto minima mollitia quis delectus optio sed, velit magnam ex harum, suscipit ea iusto.</span>
                <span>Non quia ducimus architecto, esse in illo omnis dignissimos, consequuntur cupiditate deserunt labore? Fugiat quae nobis vero laudantium officia nesciunt dignissimos temporibus totam soluta reiciendis, ipsam, consequuntur, iusto quo placeat!</span>
                <span>Fugit, corporis ipsam? Soluta minima molestias unde libero architecto facilis quis aut. Dolorem consectetur, unde quaerat minus natus cupiditate voluptas quam? Iste mollitia officiis qui dicta aut modi nesciunt! Eligendi.</span>
                <span>Delectus ea laudantium aspernatur unde nobis dolorum doloribus eligendi ipsum iste. Voluptas quaerat ducimus distinctio in dolorum est veniam beatae? Numquam maxime praesentium optio aperiam, necessitatibus eligendi dicta nemo ea!</span>
                <span>Odio sint consequatur illum? Perferendis at quia reprehenderit culpa, corrupti placeat officia eveniet doloremque facere est inventore voluptates minus temporibus laborum neque maiores ipsa odio consectetur quo unde nobis. Officiis!</span>
                <span>Quibusdam veritatis labore est quae repudiandae incidunt ab vel eius eligendi, nam ullam earum possimus assumenda ducimus deserunt eaque voluptates eos laudantium similique explicabo rem sequi cupiditate accusamus fugit? Perspiciatis.</span>
                <span>Incidunt reprehenderit aspernatur similique a cumque, quos tenetur dolorem dolores fuga consequatur tempore doloribus aliquam sint labore harum corrupti blanditiis ea iure, nobis odio porro? Placeat officiis atque deserunt cumque.</span>
                <span>Cum eum similique quae fuga provident assumenda autem debitis nulla, deleniti ea et iste vel incidunt velit ut possimus itaque sint iure nemo rem voluptates! Quod expedita eum modi cumque.</span>
              </p>
            </div>
          </v-content>

          <v-footer class="pa-3">
            <v-spacer></v-spacer>
            <div>&copy; {{ new Date().getFullYear() }} by Anke Marsolin</div>
          </v-footer>
        </v-flex>
      </v-layout>
    </v-container>
  </v-app>
</template>

<style>
  @import url('https://fonts.googleapis.com/css?family=Comfortaa|Pacifico');

  .pacifico {
    font-family: Pacifico;
  }

  .comfortaa {
    font-family: Comfortaa;
  }

  .sticky {
    position: sticky;
  }

  #subheader {
    font-size: 24px;
    text-shadow: 1px 2px 1px #333;
  }

  #header {
    font-size: 44px;
    text-shadow: 2px 3px 2px #333;
  }

  @media (max-width: 600px) {
   #header {
     font-size: 32px;
   }
   
   #subheader {
     font-size: 16px;
   }
  }
</style> 

<script>
import Carousel from './components/Carousel'

export default {
  name: 'App',
  components: {
    Carousel
  },
  data () {
    return {
      //
    }
  }
}
</script>
