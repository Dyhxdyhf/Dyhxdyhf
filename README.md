# Here you can edit all chat messages.
#
# If you encounter any issues or have questions:
# Discord: https://discord.gg/B4MAJVk
#
# Wiki: https://github.com/Angeschossen/General/wiki/Messages

general:
  prefix:
    normal: '&8[&2Lands&8] '
    help: '&8[&2Lands&8] &7Usage: '
  wYes: '&aYes'
  wNo: '&cNo'
  value:
    none: '&8None'
    unlimited: '&aunlimited'
  disabled: '&cDisabled'
  wilderness: '&aWilderness'
  server: Server
  affiliation:
    land: '&8[&2{land}&8]'
    nation: '&8[&9{nation} &8|&2 {land}&8]'
  relation:
    ally: '&aAlly'
    enemy: '&cEnemy'
    neutral: '&7Neutral'
  land:
    title:
      land: '&7%level% &7of&3 %owner%&7.'
      camp: '&7Camp of&3 %owner%&7.'
      admin: '&7This land belongs to the server.'
    default-area: Default
  area:
    description:
      default: '&7New claims will belong to this area.'
      sub: '&7This is a subarea, which can have special flags and members.'
      rented: '&aThis area is rented by player {player}.'
      sold: '&aThis area is sold to player {player}.'
  time:
    days: day(s)
    hours: hour(s)
    minutes: minute(s)
    seconds: second(s)
  status:
    online: '&aonline'
    offline: '&coffline'
  top:
    hologram:
      land:
        title: '&7&m━━━━━━━━━━━━━━<━&r &2Top 10 Lands &8(&7Total: {total}&8) &7&m━>━━━━━━━━━━━━━━'
        entry: '&c#{pos} &2{object} &7{sorting}:&3 {value}'
        footer: '&7&m━━━━━━━━━━━━━━<━&r &2Top 10 Lands &8(&7Total: {total}&8) &7&m━>━━━━━━━━━━━━━━'
      nation:
        title: '&7&m━━━━━━━━━━━━━━<━&r &2Top 10 Nations &8(&7Total: {total}&8) &7&m━>━━━━━━━━━━━━━━'
        entry: '&c#{pos} &2{object} &7{sorting}:&3 {value}'
        footer: '&7&m━━━━━━━━━━━━━━<━&r &2Top 10 Nations &8(&7Total: {total}&8) &7&m━>━━━━━━━━━━━━━━'
  integration:
    dynmap:
      land:
        description: '<div class="\&quot;infowindow\&quot;"><span style="font-size:
          200%;"><span style="color: {land_color};">{land}</span><br /></span>{title}</div>
          <ul> <li class="\&quot;infowindow\&quot;">Level: {level}</li> <li class="\&quot;infowindow\&quot;">Balance:
          {balance}</li> <li class="\&quot;infowindow\&quot;">Chunks: {chunks}</li>
          <li class="\&quot;infowindow\&quot;">Players ({members_amount}): {members}</li>
          </ul>'
        spawn: '<div class="\&quot;infowindow\&quot;"><span style="font-size: 200%;"><span
          style="color: {land_color};">Spawnpoint</span></span></div> <div class="\&quot;infowindow\&quot;"><br
          />Open to untrusted: {public}</div> <ul> <li>If this spawn is open to untrusted,
          anyone can teleport to it by executing /lands spawn {land}.</li> </ul>'
      nation:
        description: '<div class="\&quot;infowindow\&quot;"><span style="font-size:
          200%;"><span style="color: {land_color};">{land}</span><br /></span>{title}</div>
          <ul> <li class="\&quot;infowindow\&quot;">Level: {level}</li> <li class="\&quot;infowindow\&quot;">Balance:
          {balance}</li> <li class="\&quot;infowindow\&quot;">Chunks: {chunks}</li>
          <li class="\&quot;infowindow\&quot;">Players ({members_amount}): {members}</li>
          </ul> <p><strong>This land belongs to nation {nation}:</strong></p> <ul>
          <li>Level: {level_nation}</li> <li>Capital: {capital}</li> <li>Lands (total
          players: {members_amount_nation}): {lands}</li> </ul>'
      capital:
        spawn: '<div class="\&quot;infowindow\&quot;"><span style="font-size: 200%;"><span
          style="color: {land_color};">Capitals Spawnpoint</span><br /></span>This
          spawn belongs to the capital of nation {nation}.</div><div class="\&quot;infowindow\&quot;"><br
          />Open to untrusted: {public}</div><ul><li>If this spawn is open to untrusted,
          anyone can teleport to it by executing /lands spawn {land}.</li></ul>'
    bluemap:
      land:
        description: '<div class="\&quot;infowindow\&quot;"><span style="font-size:
          200%;"><span style="color: {land_color};">{land}</span><br /></span>{title}</div>
          <ul> <li class="\&quot;infowindow\&quot;">Level: {level}</li> <li class="\&quot;infowindow\&quot;">Balance:
          {balance}</li> <li class="\&quot;infowindow\&quot;">Chunks: {chunks}</li>
          <li class="\&quot;infowindow\&quot;">Players ({members_amount}): {members}</li>
          </ul>'
        spawn: 'Spawnpoint of land {land}. Open to untrusted: {public}. If this spawn
          is open to untrusted players, anyone can teleport to it by executing /lands
          spawn {land}.'
      nation:
        description: '<div class="\&quot;infowindow\&quot;"><span style="font-size:
          200%;"><span style="color: {land_color};">{land}</span><br /></span>{title}</div>
          <ul> <li class="\&quot;infowindow\&quot;">Level: {level}</li> <li class="\&quot;infowindow\&quot;">Balance:
          {balance}</li> <li class="\&quot;infowindow\&quot;">Chunks: {chunks}</li>
          <li class="\&quot;infowindow\&quot;">Players ({members_amount}): {members}</li>
          </ul> <p><strong>This land belongs to nation {nation}:</strong></p> <ul>
          <li>Level: {level_nation}</li> <li>Capital: {capital}</li> <li>Lands (total
          players: {members_amount_nation}): {lands}</li> </ul>'
      capital:
        spawn: '<div class="\&quot;infowindow\&quot;"><span style="font-size: 200%;"><span
          style="color: {land_color};">Capitals Spawnpoint</span><br /></span>This
          spawn belongs to the capital of nation {nation}.</div><div class="\&quot;infowindow\&quot;"><br
          />Open to untrusted: {public}</div><ul><li>If this spawn is open to untrusted,
          anyone can teleport to it by executing /lands spawn {land}.</li></ul>'
    squaremap:
      land:
        description: '<div class="\&quot;infowindow\&quot;"><span style="font-size:
          200%;"><span style="color: {land_color};">{land}</span><br /></span>{title}</div>
          <ul> <li class="\&quot;infowindow\&quot;">Level: {level}</li> <li class="\&quot;infowindow\&quot;">Balance:
          {balance}</li> <li class="\&quot;infowindow\&quot;">Chunks: {chunks}</li>
          <li class="\&quot;infowindow\&quot;">Players ({members_amount}): {members}</li>
          </ul>'
        spawn: '<div class="\&quot;infowindow\&quot;"><span style="font-size: 200%;"><span
          style="color: {land_color};">Spawnpoint</span></span></div> <div class="\&quot;infowindow\&quot;"><br
          />Open to untrusted: {public}</div> <ul> <li>If this spawn is open to untrusted,
          anyone can teleport to it by executing /lands spawn {land}.</li> </ul>'
      nation:
        description: '<div class="\&quot;infowindow\&quot;"><span style="font-size:
          200%;"><span style="color: {land_color};">{land}</span><br /></span>{title}</div>
          <ul> <li class="\&quot;infowindow\&quot;">Level: {level}</li> <li class="\&quot;infowindow\&quot;">Balance:
          {balance}</li> <li class="\&quot;infowindow\&quot;">Chunks: {chunks}</li>
          <li class="\&quot;infowindow\&quot;">Players ({members_amount}): {members}</li>
          </ul> <p><strong>This land belongs to nation {nation}:</strong></p> <ul>
          <li>Level: {level_nation}</li> <li>Capital: {capital}</li> <li>Lands (total
          players: {members_amount_nation}): {lands}</li> </ul>'
      capital:
        spawn: '<div class="\&quot;infowindow\&quot;"><span style="font-size: 200%;"><span
          style="color: {land_color};">Capitals Spawnpoint</span><br /></span>This
          spawn belongs to the capital of nation {nation}.</div><div class="\&quot;infowindow\&quot;"><br
          />Open to untrusted: {public}</div><ul><li>If this spawn is open to untrusted,
          anyone can teleport to it by executing /lands spawn {land}.</li></ul>'
    pl3xmap:
      land:
        description: '<div class="\&quot;infowindow\&quot;"><span style="font-size:
          200%;"><span style="color: {land_color};">{land}</span><br /></span>{title}</div>
          <ul> <li class="\&quot;infowindow\&quot;">Level: {level}</li> <li class="\&quot;infowindow\&quot;">Balance:
          {balance}</li> <li class="\&quot;infowindow\&quot;">Chunks: {chunks}</li>
          <li class="\&quot;infowindow\&quot;">Players ({members_amount}): {members}</li>
          </ul>'
        spawn: '<div class="\&quot;infowindow\&quot;"><span style="font-size: 200%;"><span
          style="color: {land_color};">Spawnpoint</span></span></div> <div class="\&quot;infowindow\&quot;"><br
          />Open to untrusted: {public}</div> <ul> <li>If this spawn is open to untrusted,
          anyone can teleport to it by executing /lands spawn {land}.</li> </ul>'
      nation:
        description: '<div class="\&quot;infowindow\&quot;"><span style="font-size:
          200%;"><span style="color: {land_color};">{land}</span><br /></span>{title}</div>
          <ul> <li class="\&quot;infowindow\&quot;">Level: {level}</li> <li class="\&quot;infowindow\&quot;">Balance:
          {balance}</li> <li class="\&quot;infowindow\&quot;">Chunks: {chunks}</li>
          <li class="\&quot;infowindow\&quot;">Players ({members_amount}): {members}</li>
          </ul> <p><strong>This land belongs to nation {nation}:</strong></p> <ul>
          <li>Level: {level_nation}</li> <li>Capital: {capital}</li> <li>Lands (total
          players: {members_amount_nation}): {lands}</li> </ul>'
      capital:
        spawn: '<div class="\&quot;infowindow\&quot;"><span style="font-size: 200%;"><span
          style="color: {land_color};">Capitals Spawnpoint</span><br /></span>This
          spawn belongs to the capital of nation {nation}.</div><div class="\&quot;infowindow\&quot;"><br
          />Open to untrusted: {public}</div><ul><li>If this spawn is open to untrusted,
          anyone can teleport to it by executing /lands spawn {land}.</li></ul>'
  map:
    wilderness: '&2▉ '
    yours: '&a▉ '
    trusted: '&e▉ '
    others: '&c▉ '
    position: '&9▉ '
    info:
      wilderness: ' &2▉ &7= Wilderness'
      yours: ' &a▉ &7= Yours'
      trusted: ' &e▉ &7= Trusted'
      others: ' &c▉ &7= Others'
      position: ' &9▉ &7= Position'
    hover:
      wilderness: '&7This chunk is wilderness. Click to claim it.'
      yours: '&7This land is owned by you. Click to show information about land&3
        {land}&7.'
      trusted: '&7You''re trusted in this land. Click to show information about land&3
        {land}&7.'
      others: '&7You''re not trusted in this land. Click to show information about
        land&3 {land}&7.'
      position: '&7This is your current position.'
  inbox:
    general:
      created: '&7Land {0} &7created.'
      post: '{0}: {1}'
    member:
      join: '&7Player {0} joined.'
      leave: '&7Player {0} left.'
      ban: '&cPlayer {0} has been banned.'
      owner: '&7Player {0} is now the new owner.'
    economy:
      upkeep:
        alert:
          normal: '&cYou need to pay&4 {0}&c in upkeep in {1}, but {2} has insufficient
            funds.'
          unclaim: '&cYou need to pay&4 {0}&c in upkeep in {1}, but {2} has insufficient
            funds. &7This will lead to some of the latest claims being unclaimed.
            Make sure to deposit some money to prevent this from happening.'
        warning: '&cCouldn''t pay upkeep cost: {0}'
        unclaim: '&cCouldn''t pay the complete upkeep cost of {0}. The last {1} claimed
          chunk(s) were unclaimed.'
        paid: '&7Paid upkeep cost: {0} New balance: {1}'
        nation: '&cNation {0} failed to pay the upkeep of {1}, from their capitals
          balance, and has been deleted.'
      bank:
        withdraw: '&cPlayer {0} withdrew {1}. New balance: {2}'
        deposit: '&7Player {0} deposited {1}. New balance: {2}'
      taxes:
        warning: '&cPlayer {0} couldn''t pay taxes.'
        untrusted: '&cPlayer {0} couldn''t pay taxes. They''re now untrusted.'
        received: '&7Received total of {0} taxes from land members. New balance: {1}'
    war:
      shield: '&7Received additional war shield time of {0}&7. Total: {1}'
      start: '&7The war against {0} &7has started. Timeout:&5 {1}'
      declaration:
        sent: '&7Declared war against {0}&7. The war will start in&5 {1}&7.'
        received: '&c{0} &cdeclared war against us. &7The war will start in&5 {1}&7.'
        mutual:
          sent: '&7Sent war request to {0}&7. They need to accept it.'
          received: '&c{0} &csent a war request. Accept: &e/wars declare {1}'
          denied: '&7Mutual war declaration denied by {0}&7.'
      surrender:
        sent: '&cSurrendered in the war. Paid {0} as tribute to the enemy.'
        received: '&7Enemy {0} &7surrendered. Received {1} as tribute.'
      end:
        won: '&7We''ve won the war against the enemy {0} &7with&3 {1} &7points. &7They
          only had&3 {2} &7points. The war took &5{3}&7.'
        draw: '&7The war ended against {0} &7eneded in a draw with&3 {1} &7points.'
        lost: '&7We''ve lost the war against the enemy {0} &7with&3 {1} &7points.
          &7They had&3 {2} &7points. The war took &5{3}&7.'
    nation:
      general:
        created: '&7Nation {0} &7created.'
      member:
        join: '&7Land {0} joined.'
        leave: '&7Land {0} left.'
      economy:
        upkeep:
          warning: '&cCouldn''t pay the upkeep cost of {0}.'
          paid: '&7Paid upkeep cost: - {0}'
        taxes:
          warning: '&cLand {0} couldn''t pay taxes.'
          untrusted: '&cLand {0} couldn''t pay taxes. They were removed.'
          received: '&7Received total of {0} taxes from lands. New balance: {1}'
    relation:
      ally:
        offer: '&7{0} &7wants to be allies with us.'
        accepted: '&7We''re now allies with {0}&7.'
        remove: '&7We''re no longer allies with {0}&7.'
      enemy:
        add: '&7We''re now enemies to {0}&7.'
        offer: '&7{0} &7wants to be neutral to us.'
        accepted: '&7We''re no longer enemies to {0}&7.'
  wars:
    object:
      enemy: '&cEnemy'
      ally: '&aAlly'
    nametag:
      enemy: '&cENEMY &8| '
      ally: '&aALLY &8| '
    state:
      preparation: '&aPreparation'
      fight: '&cFight'
  command:
    argument:
      optional: '&8<&e{arg}&8>'
      required: '&8[&e{arg}&8]'
      type:
        land: land
        nation: nation
        cmd: cmd
        area: area
        player: player
        name: name
        number: number
        confirm: confirm
        funds: funds
        menu: menu
        world: world
        args: arguments
        page: page
        database: database
        holder: land | nation
        plugin: plugin
        role: role
        flag: flag
        radius: radius
        context: context
        boolean: true | false
        flag_or_all: flag | all
        amount: amount
        tribute: tribute
        y-min: y-min
        y-max: y-max
        silent: silent
        sorting: sorting
        preparation_time: preparation time
        category: category


help:
  help:
    root:
      header: '[NoPrefix][T]&7&l&m━━&e&l<<<<&7&l&m━[H]&7Click here to navigate to
        the previous page.[/H][C]{cmd} {previous}[/C][/T] &2Lands Commands &7Page&3
        {page} &8/&3 {pages} [T]&7&l&m━&e&l>>>>&7&l&m━━[H]&7Click here to go to the
        next page.[/H][C]{cmd} {next}[/C][/T]'
      footer: |
        [NoPrefix]
        &7Click on the arrows below to navigate.
        [T]&7&l&m━━&e&l<<<<&7&l&m━[H]&7Click here to navigate to the previous page.[/H][C]{cmd} {previous}[/C][/T] &2Lands Commands &7Page&3 {page} &8/&3 {pages} [T]&7&l&m━&e&l>>>>&7&l&m━━[H]&7Click here to go to the next page.[/H][C]{cmd} {next}[/C][/T]
    sub:
      unknown: |
        &cThe subcommand&4 {command} &cdoesn't exist.
          [T]&7✖ View commands: &3/{cmd} &8[CLICK][H]&7Click here to get a list of available commands[/H][C]{cmd}[/C][/T]
      header: '[NoPrefix][T]&7&l&m━━━━━&e&l<<<<&7&l&m━[H]&7Click here to navigate
        to the previous page.[/H][C]{cmd} {previous}[/C][/T] &2Sub Commands &7Page&3
        {page} &8/&3 {pages} [T]&7&l&m━&e&l>>>>&7&l&m━━━━━[H]&7Click here to go to
        the next page.[/H][C]{cmd} {next}[/C][/T]'
      footer: |
        [NoPrefix]
        &7Click on the arrows below to navigate.
        [T]&7&l&m━━━━━&e&l<<<<&7&l&m━[H]&7Click here to navigate to the previous page.[/H][C]{cmd} {previous}[/C][/T] &2Sub Commands &7Page&3 {page} &8/&3 {pages} [T]&7&l&m━&e&l>>>>&7&l&m━━━━━[H]&7Click here to go to the next page.[/H][C]{cmd} {next}[/C][/T]
  command:
    lands:
      help: '[T]&e{parent} {subcmd} {args} - &7Get help[H]&7Click to execute.[/H][C]{fullcmd}[/C][/T]'
      edit: '[T]&e{parent} {subcmd} {args} &8- &7Enter edit mode for land[H]&7The
        edit land is used for commands like /lands claim. &7Click to copy.[/H][SC]{fullcmd}[/SC][/T]'
      confirmtp: '[T]&e{parent} {subcmd} &8- &7Confirm unsafe teleport destination[H]&7Click
        to execute.[/H][C]{fullcmd}[/C][/T]'
      claim:
        main: '[T]&e{parent} {subcmd} {args} &8- &7Claim chunk(s)[H]&7Claim using
          different techniques &8(&e/selection&7, fill, auto, radius&8)&7. &7Click
          to copy.[/H][SC]{fullcmd}[/SC][/T]'
        auto: '[T]&e{parent} {subcmd} &8- &7Claim while moving[H]&7This will claim
          all chunks that you enter, while moving. Click to execute.[/H][C]{fullcmd}[/C][/T]'
        fill: '[T]&e{parent} {subcmd} &8- &7Claim chunks inside shape[H]&7Claim all
          chunks inside a shape to fill it. Click to execute.[/H][C]{fullcmd}[/C][/T]'
        radius: '[T]&e{parent} {subcmd} {args} &8- &7Claim radius[H]&7Claim all chunks
          in a specified radius. Click to copy.[/H][SC]{fullcmd}[/SC][/T]'
      
      create: '[T]&e{parent} {subcmd} {args} &8- &7Create land[H]&7Click to copy.[/H][SC]{fullcmd}[/SC][/T]'
      createcamp: '[T]&e{parent} {subcmd} {args} &8- &7Create camp[H]&7Click to copy.[/H][SC]{fullcmd}[/SC][/T]'
      merge: '[T]&e{parent} {subcmd} {args} &8- &7Merge land into your current[H]&7Click
        to copy.[/H][SC]{fullcmd}[/SC][/T]'
      storage: '[T]&e{parent} {subcmd} &8- &7Open the land storage[H]&7Click to execute.[/H][C]{fullcmd}[/C][/T]'
      leave: '[T]&e{parent} {subcmd} {args} &8- &7Leave a land or area.[H]&7If you
        don''t specify a land, you''ll leave the area at your current position. &7Click
        to copy.[/H][SC]{fullcmd}[/SC][/T]'
      unclaim:
        main: '[T]&e{parent} {subcmd} &8- &7Unclaim chunk[H]&7This also supports &e/lands
          selection&7. &7Click to execute.[/H][C]{fullcmd}[/C][/T]'
        radius: '[T]&e{parent} {subcmd} {args} &8- &7Unclaim radius[H]&7Unclaim all
          chunks in a specified radius. Click to copy.[/H][SC]{fullcmd}[/SC][/T]'
        auto: '[T]&e{parent} {subcmd} &8- &7Unclaim while moving[H]&7This will unclaim
          all chunks that you enter, while moving. Click to execute.[/H][C]{fullcmd}[/C][/T]'
        all: '[T]&e{parent} {subcmd} &8- &7Unclaim all chunks[H]&7Click to copy.[/H][SC]{fullcmd}[/SC][/T]'
      delete: '[T]&e{parent} delete {args} &8- &7Delete land[H]&7Click to copy.[/H][SC]{fullcmd}[/SC][/T]'
      trust: '[T]&e{parent} {subcmd} {args} &8- &7Trust player[H]&7Use * as the area
        name to trust the player to the whole land. &7Click to copy.[/H][SC]{fullcmd}[/SC][/T]'
      untrust: '[T]&e{parent} {subcmd} {args} &8- &7Untrust player[H]&7Use * as the
        area name to untrust the player from the whole land. &7Click to copy.[/H][SC]{fullcmd}[/SC][/T]'
      setRole: '[T]&e{parent} {subcmd} {args} &8- &7Set role[H]&7Click to copy.[/H][SC]{fullcmd}[/SC][/T]'
      accept: '[T]&e{parent} {subcmd} {args} &8- &7Accept invite[H]&7You can view
        all received invites by executing /lands invites. &7Click to copy.[/H][SC]{fullcmd}[/SC][/T]'
      deny: '[T]&e{parent} {subcmd} {args} &8- &7Deny invite[H]&7Click to copy.[/H][SC]{fullcmd}[/SC][/T]'
      view:
        main: '[T]&e{parent} {subcmd} {args} &8- &7Information about claims[H]&7This
          command will visualize nearby claims too. &7Click to copy.[/H][SC]{fullcmd}[/SC][/T]'
        disable: '[T]&e{parent} {subcmd} &8- &7Disable visualization[H]&7Disable the
          current &e/lands view &7visualization. Click to execute.[/H][C]{fullcmd}[/C][/T]'
        here: '[T]&e{parent} {subcmd} &8- &7Visualize subarea[H]&7Visualize the subarea
          you''re current standing in. &7Click to execute.[/H][C]{fullcmd}[/C][/T]'
        stay: '[T]&e{parent} {subcmd} &8- &7Lock y position[H]&7The visualization
          will no longer follow your height. &7Click to execute.[/H][C]{fullcmd}[/C][/T]'
      
      menu: '[T]&e{parent} {subcmd} {args} &8- &7Open menu[H]&7Click to copy.[/H][SC]{fullcmd}[/SC][/T]'
      setSpawn: '[T]&e{parent} {subcmd} &8- &7Set landspawn[H]&7Click to copy.[/H][SC]{fullcmd}[/SC][/T]'
      spawn: '[T]&e{parent} {subcmd} {args} &8- &7Teleport to land[H]&7Click to copy.[/H][SC]{fullcmd}[/SC][/T]'
      wild: '[T]&e{parent} {subcmd} {args} &8- &7Teleport to random location[H]&7Click
        to execute.[/H][C]{fullcmd}[/C][/T]'
      top: '[T]&e{parent} {subcmd} &8- &7Show top lands[H]&7Click to execute.[/H][C]{fullcmd}[/C][/T]'
      selection:
        main: '[T]&e{parent} {subcmd} {args} &8- &7Selection mode[H]&7With this command
          you can resize a subarea or expand your selection to infinite y levels.
          &7Click to execute.[/H][C]{fullcmd}[/C][/T]'
        assign: '[T]&e{parent} {subcmd} {args} &8- &7Resize subarea[H]&7Click to copy.[/H][SC]{fullcmd}[/SC][/T]'
        expand: '[T]&e{parent} {subcmd} &8- &7Expand selection[H]&7Click to execute.[/H][C]{fullcmd}[/C][/T]'
      chat: '[T]&e{parent} {subcmd} {args} &8- &7Land chat[H]&7Click to copy.[/H][SC]{fullcmd}[/SC][/T]'
      rename: '[T]&e{parent} {subcmd} {args} &8- &7Rename land[H]&7Click to copy.[/H][SC]{fullcmd}[/SC][/T]'
      teleport: '[T]&e{parent} {subcmd} {args} &8- &7Teleport to chunk[H]&7Click to
        copy.[/H][SC]{fullcmd}[/SC][/T]'
      invites: '[T]&e{parent} {subcmd} &8- &7Show received invites[H]&7Click to execute.[/H][C]{fullcmd}[/C][/T]'
      info: '[T]&e{parent} {subcmd} {args} &8- &7View information about land[H]&7Click
        to execute.[/H][C]{fullcmd}[/C][/T]'
      player: '[T]&e{parent} {subcmd} {args} &8- &7View information about player[H]&7Click
        to copy.[/H][SC]{fullcmd}[/SC][/T]'
      map:
        main: '[T]&e{parent} {subcmd} &8- &7View map[H]&7Click to execute.[/H][C]{fullcmd}[/C][/T]'
        chat: '[T]&e{parent} {subcmd} &8- &7View map in chat[H]&7Click to execute.[/H][C]{fullcmd}[/C][/T]'
      balance: '[T]&e{parent} {subcmd} {args} &8- &7Check balance[H]&7Click to copy.[/H][SC]{fullcmd}[/SC][/T]'
      deposit: '[T]&e{parent} {subcmd} {args} &8- &7Deposit money[H]&7Click to copy.[/H][SC]{fullcmd}[/SC][/T]'
      withdraw: '[T]&e{parent} {subcmd} {args} &8- &7Withdraw money[H]&7Click to copy.[/H][SC]{fullcmd}[/SC][/T]'
      list: '[T]&e{parent} {subcmd} {args} &8- &7List all lands[H]&7Click to execute.[/H][C]{fullcmd}[/C][/T]'
      assign: '[T]&e{parent} {subcmd} {args} &8- &7Assign selection to area[H]&7Click
        to copy.[/H][SC]{fullcmd}[/SC][/T]'
      setowner: '[T]&e{parent} {subcmd} {args} &8- &7Transfer ownership[H]&7Click
        to copy.[/H][SC]{fullcmd}[/SC][/T]'
      ban: '[T]&e{parent} {subcmd} {args} &8- &7Ban player[H]&7Click to copy.[/H][SC]{fullcmd}[/SC][/T]'
      unban: '[T]&e{parent} {subcmd} {args} &8- &7Unban player[H]&7Click to copy.[/H][SC]{fullcmd}[/SC][/T]'
      taxes: '[T]&e{parent} {subcmd} &8- &7Show upcoming tax payments[H]&7Click to
        execute.[/H][C]{fullcmd}[/C][/T]'
      upkeep: '[T]&e{parent} {subcmd} &8- &7Show upcoming upkeep payments.[H]&7Click
        to execute.[/H][C]{fullcmd}[/C][/T]'
      unstuck: '[T]&e{parent} {subcmd} &8- &7Teleport out of traps[H]&7In case you
        got stuck in a land. &7Click to execute.[/H][C]{fullcmd}[/C][/T]'
      claimlist: '[T]&e{parent} {subcmd} {args} &8- &7List claims of your land[H]&7This
        command will show you all /lands claim''s of your land. &7Click to execute.[/H][C]{fullcmd}[/C][/T]'
      rent:
        main: '[T]&e{parent} {subcmd} {args} &8- &7Manage rental[H]&7Manage rented
          area at your current position. &7Click to copy.[/H][SC]{fullcmd}[/SC][/T]'
        cancel: '[T]&e{parent} {subcmd} &8- &7Cancel rental[H]&7Cancel your rental
          of the sub area at your current position. &7Click to execute.[/H][C]{fullcmd}[/C][/T]'
        info: '[T]&e{parent} {subcmd} &8- &7Show info[H]&7Show information about the
          rental of the sub area at your current position. &7Click to execute.[/H][C]{fullcmd}[/C][/T]'
        list: '[T]&e{parent} {subcmd} &8- &7View all rental offers[H]&7View all rental
          offers from all lands. &7Click to execute.[/H][C]{fullcmd}[/C][/T]'
        remove:
          main: '[T]&e{parent} {subcmd} {args} &8- &7Manage current rental[H]&7Manage
            rented area at your current position. &7Click to copy.[/H][SC]{fullcmd}[/SC][/T]'
          offer: '[T]&e{parent} {subcmd} &8- &7Remove offer[H]&7Players won''t be
            able to extend their rental. &7Click to execute.[/H][C]{fullcmd}[/C][/T]'
          tenant: '[T]&e{parent} {subcmd} &8- &7Remove tenant[H]&7Remove the current
            tenant by paying a compensation to them. &7Click to execute.[/H][C]{fullcmd}[/C][/T]'
      level: '[T]&e{parent} {subcmd} &8- &7View level progress[H]&7View the progress
        of unlocking the next level and benefits of the current and the next level.
        &7Click to execute.[/H][C]{fullcmd}[/C][/T]'
      relations:
        main: '[T]&e{parent} {subcmd} {args} &8- &7Manage relations[H]&7Add lands
          and nations as your allies or enemies. Click to copy.[/H][SC]{fullcmd}[/SC][/T]'
        allies:
          main: '[T]&e{parent} {subcmd} {args} &8- &7Manage allies[H]&7Add lands and
            nations as your allies. Click to copy.[/H][SC]{fullcmd}[/SC][/T]'
          add: '[T]&e{parent} {subcmd} {args} &8- &7Add allly[H]&7Add a land or nation
            as your ally. Click to copy.[/H][SC]{fullcmd}[/SC][/T]'
          remove: '[T]&e{parent} {subcmd} {args} &8- &7Remove ally[H]&7End relation
            with an ally. Click to copy.[/H][SC]{fullcmd}[/SC][/T]'
        enemies:
          main: '[T]&e{parent} {subcmd} {args} &8- &7Manage enemies[H]&7Add lands
            and nations as your enemies. Click to copy.[/H][SC]{fullcmd}[/SC][/T]'
          add: '[T]&e{parent} {subcmd} {args} &8- &7Add enemy[H]&7Declare a land or
            nation an enemy. Click to copy.[/H][SC]{fullcmd}[/SC][/T]'
          remove: '[T]&e{parent} {subcmd} {args} &8- &7Remove enemy[H]&7Send neutralization
            request to an enemy. Click to copy.[/H][SC]{fullcmd}[/SC][/T]'
      
      admin:
        main: '[T]&e{parent} {subcmd} {args} &8- &7Admin commands[H]&7Click to copy.[/H][SC]{fullcmd}[/SC][/T]'
        listperms: '[T]&e{parent} {subcmd} {args} &8- &7List permissions a player
          has[H]&7Click to copy.[/H][SC]{fullcmd}[/SC][/T]'
        debug: '[T]&e{parent} {subcmd} &8- &7Shows loaded data stats[H]&7Click to
          execute.[/H][C]{fullcmd}[/C][/T]'
        reload: '[T]&e{parent} {subcmd} &8- &7Reload config and messages[H]&7Click
          to execute.[/H][C]{fullcmd}[/C][/T]'
        about: '[T]&e{parent} {subcmd} &8- &7Show information about Lands[H]&7Click
          to execute.[/H][C]{fullcmd}[/C][/T]'
        chatspy: '[T]&e{parent} {subcmd} {args} &8- &7Listen to chat[H]&7Click to
          copy.[/H][SC]{fullcmd}[/SC][/T]'
        dismiss: '[T]&e{parent} {subcmd} {args} &8- &7Dismiss notes[H]&7Click to execute.[/H][C]{fullcmd}[/C][/T]'
        import: '[T]&e{parent} {subcmd} {args} &8- &7Import claims from 3rd party[H]&7Click
          to copy.[/H][SC]{fullcmd}[/SC][/T]'
        menu: '[T]&e{parent} {subcmd} {args} &8- &7Open admin menu[H]&7Click to execute.[/H][C]{fullcmd}[/C][/T]'
        deleteinactive: '[T]&e{parent} {subcmd} &8- &7Delete inactive players/lands[H]&7Click
          to execute.[/H][C]{fullcmd}[/C][/T]'
        migratedb: '[T]&e{parent} {subcmd} {args} &8- &7Migrate database[H]&7Click
          to copy.[/H][SC]{fullcmd}[/SC][/T]'
        player:
          main: '[T]&e{parent} {subcmd} {args} &8- &7Special player administration[H]&7Click
            to copy.[/H][SC]{fullcmd}[/SC][/T]'
          menu: '[T]&e{parent} {subcmd} &8- &7Open menu of player[H]&7Click to copy.[/H][SC]{fullcmd}[/SC][/T]'
          delete: '[T]&e{parent} {subcmd} &8- &7Delete player and his lands[H]&7Click
            to copy.[/H][SC]{fullcmd}[/SC][/T]'
          give:
            main: '[T]&e{parent} {subcmd} {args} &8- &7Give to player[H]&7Click to
              copy.[/H][SC]{fullcmd}[/SC][/T]'
            camp: '[T]&e{parent} {subcmd} {args} &8- &7Give camp items[H]&7Click to
              copy.[/H][SC]{fullcmd}[/SC][/T]'
            captureflag: '[T]&e{parent} {subcmd} {args} &8- &7Give to captureblocks[H]&7Click
              to copy.[/H][SC]{fullcmd}[/SC][/T]'
            claimblock: '[T]&e{parent} {subcmd} {args} &8- &7Give claimblocks[H]&7Click
              to copy.[/H][SC]{fullcmd}[/SC][/T]'
            permission:
              main: '[T]&e{parent} {subcmd} {args} &8- &7Modify numbered permissions[H]&7Click
                to copy.[/H][SC]{fullcmd}[/SC][/T]'
              chunks: '[T]&e{parent} {subcmd} {args} &8- &7Modify max. chunks[H]&7Click
                to copy.[/H][SC]{fullcmd}[/SC][/T]'
              chunks-support: '[T]&e{parent} {subcmd} {args} &8- &7Modify support
                chunks[H]&7Click to copy.[/H][SC]{fullcmd}[/SC][/T]'
              lands: '[T]&e{parent} {subcmd} {args} &8- &7Modify max. member lands[H]&7Click
                to copy.[/H][SC]{fullcmd}[/SC][/T]'
              members: '[T]&e{parent} {subcmd} {args} &8- &7Modify max. members[H]&7Click
                to copy.[/H][SC]{fullcmd}[/SC][/T]'
              ownlands: '[T]&e{parent} {subcmd} {args} &8- &7Modify max. own lands[H]&7Click
                to copy.[/H][SC]{fullcmd}[/SC][/T]'
        
        resetworld: '[T]&e{parent} {subcmd} {args} &8- &7Delete all claims in world[H]&7Click
          to copy.[/H][SC]{fullcmd}[/SC][/T]'
        hologram:
          main: '[T]&e{parent} {subcmd} {args} &8- &7Manage leaderboard holograms[H]&7Click
            to copy.[/H][SC]{fullcmd}[/SC][/T]'
          create: '[T]&e{parent} {subcmd} {args} &8- &7Create hologram[H]&7Click to
            copy.[/H][SC]{fullcmd}[/SC][/T]'
          delete: '[T]&e{parent} {subcmd} &8- &7Delete nearby hologram[H]&7Click to
            execute.[/H][C]{fullcmd}[/C][/T]'
          list: '[T]&e{parent} {subcmd} &8- &7List holograms[H]&7Click to execute.[/H][C]{fullcmd}[/C][/T]'
        land:
          main: '[T]&e{parent} {subcmd} {args} &8- &7Special land administration[H]&7Click
            to copy.[/H][SC]{fullcmd}[/SC][/T]'
          setflag: '[T]&e{parent} {subcmd} {args} &8- &7Set flag state[H]&7Click to
            copy.[/H][SC]{fullcmd}[/SC][/T]'
          resetflag: '[T]&e{parent} {subcmd} {args} &8- &7Reset flag state to roles.yml[H]&7Click
            to copy.[/H][SC]{fullcmd}[/SC][/T]'
          addrole: '[T]&e{parent} {subcmd} {args} &8- &7Add custom role from roles.yml[H]&7Click
            to copy.[/H][SC]{fullcmd}[/SC][/T]'
          menu: '[T]&e{parent} {subcmd} &8- &7Open land menu[H]&7Click to execute.[/H][C]{fullcmd}[/C][/T]'
          syncpermissions: '[T]&e{parent} {subcmd} &8- &7Sync permission limits[H]&7Click
            to execute.[/H][C]{fullcmd}[/C][/T]'
          bank:
            main: '[T]&e{parent} {subcmd} &8- &7Edit bank balance[H]&7Click to copy.[/H][SC]{fullcmd}[/SC][/T]'
            modify: '[T]&e{parent} {subcmd} {args} &8- &7Add (+) or remove (-) funds[H]&7Click
              to copy.[/H][SC]{fullcmd}[/SC][/T]'
            set: '[T]&e{parent} {subcmd} {args} &8- &7Set funds[H]&7Click to copy.[/H][SC]{fullcmd}[/SC][/T]'
          shield:
            main: '[T]&e{parent} {subcmd} &8- &7Edit shield time[H]&7Click to copy.[/H][SC]{fullcmd}[/SC][/T]'
            modify: '[T]&e{parent} {subcmd} {args} &8- &7Add (+) or remove (-) time[H]&7Click
              to copy.[/H][SC]{fullcmd}[/SC][/T]'
            set: '[T]&e{parent} {subcmd} {args} &8- &7Set time[H]&7Click to copy.[/H][SC]{fullcmd}[/SC][/T]'
    
    wars:
      declare: '[T]&e{parent} {subcmd} {args} - &7Declare war[H]&7Click to copy.[/H][SC]{fullcmd}[/SC][/T]'
      info:
        main: '[T]&e{parent} {subcmd} {args} &8- &7Info about war[H]&7Click to execute.[/H][C]{fullcmd}[/C][/T]'
        captureflag: '[T]&e{parent} {subcmd} &8- &7View captureflag recipe[H]&7Click
          to execute.[/H][C]{fullcmd}[/C][/T]'
      menu: '[T]&e{parent} {subcmd} {args} &8- &7Open war menu[H]&7Click to execute.[/H][C]{fullcmd}[/C][/T]'
      deny: '[T]&e{parent} {subcmd} &8- &7Deny mutual war declaration[H]&7Click to
        execute.[/H][C]{fullcmd}[/C][/T]'
      spawn: '[T]&e{parent} {subcmd} &8- &7Teleport to enemy[H]&7Click to execute.[/H][C]{fullcmd}[/C][/T]'
      
      admin:
        main: '[T]&e{parent} {subcmd} {args} &8- &7Special war administration[H]&7Click
          to copy.[/H][SC]{fullcmd}[/SC][/T]'
        start: '[T]&e{parent} {subcmd} {args} &8- &7Start war[H]&7Click to copy.[/H][SC]{fullcmd}[/SC][/T]'
        end: '[T]&e{parent} {subcmd} {args} &8- &7End war[H]&7Click to copy.[/H][SC]{fullcmd}[/SC][/T]'
    
    nations:
      chat: '[T]&e{parent} {subcmd} {args} &8- &7Nation chat[H]&7Click to copy.[/H][SC]{fullcmd}[/SC][/T]'
      trust: '[T]&e{parent} {subcmd} {args} &8- &7Invite land[H]&7Click to copy.[/H][SC]{fullcmd}[/SC][/T]'
      untrust: '[T]&e{parent} {subcmd} {args} &8- &7Remove land[H]&7Click to copy.[/H][SC]{fullcmd}[/SC][/T]'
      accept: '[T]&e{parent} {subcmd} {args} &8- &7Accept invite[H]&7Click to copy.[/H][SC]{fullcmd}[/SC][/T]'
      deny: '[T]&e{parent} {subcmd} {args} &8- &7Deny invite[H]&7Click to copy.[/H][SC]{fullcmd}[/SC][/T]'
      menu: '[T]&e{parent} {subcmd} {args} &8- &7Menu[H]&7Click to execute.[/H][C]{fullcmd}[/C][/T]'
      create: '[T]&e{parent} {subcmd} {args} &8- &7Create nation[H]&7Click to copy.[/H][SC]{fullcmd}[/SC][/T]'
      delete: '[T]&e{parent} {subcmd} &8- &7Delete nation[H]&7Click to copy.[/H][SC]{fullcmd}[/SC][/T]'
      leave: '[T]&e{parent} {subcmd} &8- &7Leave nation[H]&7Click to execute.[/H][C]{fullcmd}[/C][/T]'
      spawn: '[T]&e{parent} {subcmd} &8- &7Capital spawn[H]&7Click to copy.[/H][SC]{fullcmd}[/SC][/T]'
      rename: '[T]&e{parent} {subcmd} &8- &7Rename nation[H]&7Click to copy.[/H][SC]{fullcmd}[/SC][/T]'
      setcapital: '[T]&e{parent} {subcmd} {args} &8- &7Set capital[H]&7Click to copy.[/H][SC]{fullcmd}[/SC][/T]'
      level: '[T]&e{parent} {subcmd} &8- &7View level progress[H]&7View the progress
        of unlocking the next level and benefits of the current and the next level.
        &7Click to execute.[/H][C]{fullcmd}[/C][/T]'
      info: '[T]&e{parent} {subcmd} {args} &8- &7View information about nation[H]&7Click
        to execute.[/H][C]{fullcmd}[/C][/T]'
      list: '[T]&e{parent} {subcmd} {args} &8- &7List all nations[H]&7Click to execute.[/H][C]{fullcmd}[/C][/T]'
      top: '[T]&e{parent} {subcmd} &8- &7Show top nations[H]&7Click to execute.[/H][C]{fullcmd}[/C][/T]'
      relations:
        main: '[T]&e{parent} {subcmd} {args} &8- &7Manage relations[H]&7Add lands
          and nations as your allies or enemies. Click to copy.[/H][SC]{fullcmd}[/SC][/T]'
        allies:
          main: '[T]&e{parent} {subcmd} {args} &8- &7Manage allies[H]&7Add lands and
            nations as your allies. Click to copy.[/H][SC]{fullcmd}[/SC][/T]'
          add: '[T]&e{parent} {subcmd} {args} &8- &7Add allly[H]&7Add a land or nation
            as your ally. Click to copy.[/H][SC]{fullcmd}[/SC][/T]'
          remove: '[T]&e{parent} {subcmd} {args} &8- &7Remove ally[H]&7End relation
            with an ally. Click to copy.[/H][SC]{fullcmd}[/SC][/T]'
        enemies:
          main: '[T]&e{parent} {subcmd} {args} &8- &7Manage enemies[H]&7Add lands
            and nations as your enemies. Click to copy.[/H][SC]{fullcmd}[/SC][/T]'
          add: '[T]&e{parent} {subcmd} {args} &8- &7Add enemy[H]&7Declare a land or
            nation an enemy. Click to copy.[/H][SC]{fullcmd}[/SC][/T]'
          remove: '[T]&e{parent} {subcmd} {args} &8- &7Remove enemy[H]&7Send neutralization
            request to an enemy. Click to copy.[/H][SC]{fullcmd}[/SC][/T]'

lands:
  message:
    inbox:
      new:
        posts: |
          &7There are {amount} new messages posted by members of your land&2 {land}&7. Latest: {latest}
            [T]&7✖ View them: &e/{cmd} &8[CLICK][H]&7Click to view them[/H][C]{cmd}[/C][/T]
        general: |
          &7There are {amount} new inbox messages for the land&2 {land}&7. Latest: {latest}
            [T]&7✖ View them: &e/{cmd} &8[CLICK][H]&7Click to view them[/H][C]{cmd}[/C][/T]
    feature-disabled: '&cThis feature was disabled by an administrator. &8They need
      to enable setting ''{setting}'' in config, to let you use this feature.'
    war: '&cYou can''t do this right now. &7{object} &7is currently engaged in a war
      against {enemy}&7. &7Please try again after the war is over.'
    combat:
      tag: '#b#[config]color:purple,style:solid[/config]&7Combat tag:&5 {time}'
    flags:
      block_place: '&cYou''re not allowed to place blocks here (&cArea:&4 {area} &cLand:&4
        {land}&c). &8Flag: {flag}'
      block_break: '&cYou''re not allowed to break blocks here (&cArea:&4 {area} &cLand:&4
        {land}&c). &8Flag: {flag}'
      block_ignite: '&cYou''re not allowed to ignite blocks here (&cArea:&4 {area}
        &cLand:&4 {land}&c). &8Flag: {flag}'
      interact_general: '&cYou''re not allowed to interact here (&cArea:&4 {area}
        &cLand:&4 {land}&c). &8Flag: {flag}'
      interact_door: '&cYou''re not allowed to open doors here (&cArea:&4 {area} &cLand:&4
        {land}&c). &8Flag: {flag}'
      interact_mechanism: '&cYou''re not allowed to use mechanisms here (&cArea:&4
        {area} &cLand:&4 {land}&c). &8Flag: {flag}'
      interact_container: '&cYou''re not allowed to open containers here (&cArea:&4
        {area} &cLand:&4 {land}&c). &8Flag: {flag}'
      interact_villager: '&cYou''re not allowed to trade with villagers here (&cArea:&4
        {area} &cLand:&4 {land}&c). &8Flag: {flag}'
      fly: '&cYou''re not allowed to fly here (&cArea:&4 {area} &cLand:&4 {land}&c).
        &8Flag: {flag}'
      spawn_teleport: '&cYou''re not allowed to teleport to the spawn of land&4 {land}&c.
        &7They can adjust their role settings to allow teleportation to their spawn
        for you. &8Flag: {flag}'
      land_enter: '&cYou''re not allowed to enter the area&4 {area} &cof land&4 {land}&c
        (&cArea:&4 {area} &cLand:&4 {land}&c). &7You were teleported to your previous
        location. &8Flag: {flag}'
      vehicle_use: '&cYou''re not allowed to use vehicles here (&cArea:&4 {area} &cLand:&4
        {land}&c). &8Flag: {flag}'
      item_pickup: '&cYou''re not allowed to drop and pickup items here (&cArea:&4
        {area} &cLand:&4 {land}&c). &8Flag: {flag}'
      ender_pearl: '&cYou''re not allowed to use this item to teleport into the area&6
        {area} &cof land&4 {land}&c. &8Flag: {flag}'
      attack_animal: '&cYou''re not allowed to attack animals here (&cArea:&4 {area}
        &cLand:&4 {land}&c). &8Flag: {flag}'
      attack_monster: '&cYou''re not allowed to attack monsters here (&cArea:&4 {area}
        &cLand:&4 {land}&c). &7They also won''t be able to attack you. &8Flag: {flag}'
    rented:
      edit: '&cYou can''t do this while the area&4 {area}&c is being rented or sold.
        &7Remove tenant: &e/{cmd}'
      tenant: '&cYou can''t edit the tenant&4 {player}&c of area&4 {area}&c. &7Remove
        tenant: &e/{cmd}'
    noaccess:
      wilderness: '&cYou''re not allowed to do this in the wilderness. &8Flag: {flag}'
      area: '&cYou''re not allowed to do this in this area (&cArea:&4 {area} &cLand:&4
        {land}&c). &8Flag: {flag}'
      banned: '&cYou''re not allowed to enter this area. &7You''ve been banned from
        this area &8(&7Area:&6 {area} &7Land:&2 {land}&8)&7.'
      claimblock: '&cYou don''t own this claimblock. &7It belongs to&3 {player}&7.'
      
      combat:
        attacker: '&cYou''re not allowed to attack players here. &7This area belongs
          to land&2 {land}&7.'
        target: '&cYour target isn''t allowed to attack players here. &7You can''t
          fight with them here. &7This area belongs to land&2 {land}&7.'
        ally: '&cYou can''t attack this player in wilderness, because he is a member
          in one of your lands. &7Arena fights can be done in your land by allowing
          pvp in the role settings.'
        wilderness: '&cYou can''t attack this player, because he''s in wilderness
          and you''re standing in claimed land.'
    area:
      exists: '&cA area with the name&4 {area} &calready exists in land&4 {land}&c.'
      not-exist: '&cThe area&4 {area} &cdoesn''t exist in land&4 {land}&c.'
      default: '&cYou can''t do this with the default area&4 {area} &cof land&4 {land}&c.'
    introduction:
      container-placement: |
        &cYou placed a container in the wilderness. &7Other players may be able to open it and take items.
          [T]&7✖ Secure it: &e/{cmd} &8[CLICK][H]&7Claim land at this location to secure it.[/H][C]{fullcmd}[/C][/T]
    event:
      fly:
        counter: '#t#&6Fly-Mode disabling[newline]&7in &3{sec} &7second(s)'
        disabled: '&cYour fly mode has been disabled. &7You''re not allowed to fly
          here.'
      elytra:
        counter: '#t#&6Elytra disabling[newline]&7in &3{sec} &7second(s)'
        disabled: '&cYour elytra gliding has been disabled. &7You''re not allowed
          to use elytras here.'
      enter:
        land: '#t#[config]in:5,stay:40,out:2[/config]&2&l{land}[newline]&3{title}'
        camp: '#t#[config]in:5,stay:40,out:2[/config]&2&l{land}[newline]&3{title}'
        admin: '#t#[config]in:5,stay:40,out:2[/config]&2&l{land}[newline]{title}'
        pvp-warning: '#a#&cYou entered a pvp zone.'
      leave:
        land: '#t#[config]in:5,stay:30,out:2[/config]&2&lWilderness[newline]&7Feel
          the wild'
        camp: '#t#[config]in:5,stay:30,out:2[/config]&2&lWilderness[newline]&7Feel
          the wild'
        admin: '#t#[config]in:5,stay:30,out:2[/config]&2&lWilderness[newline]&7Feel
          the wild'
      level:
        up: '#t#&6{object}[newline]&7leveled up: {level}'
        down: '#t#&6{object}[newline]&7leveled down to: {level}'
      inbox: '&eInbox &8- {object}&8: {message}'
    teleportation:
      already: '&cYou can''t start a second teleportation. There''s already a teleportation
        in progress. &7Please wait until it''s done.'
      started: '&7Teleportation process started. Teleporting in&5 {sec} seconds&7.
        Please don''t move.'
      cmd: '&cYou can''t use any commands while being teleported. &7Please wait another&5
        {sec} seconds &7until the teleportation has been finished.'
      combat: '&cYou can''t teleport while being engaged in combat. &7Please wait
        another&5 {time} &7while you don''t attack anyone.'
      progress: '#b#[config]color:purple,style:solid[/config]&7Wait&5 {time} &7Second(s)
        until Teleportation.'
      cancelled: '&cYour teleportation has been cancelled. &7Please don''t move while
        you''re waiting&5 {sec} &7seconds for teleportation.'
      chunk: '#t#&6Teleported[newline]&7X: {x} Z: {z} Cost:&c {cost}'
      plugin: '&cTeleportation has been cancelled by a 3rd party plugin. &7Please
        check your other plugins. &7This is not a Lands issue.'
      unsafe: |
        &7The teleportation has been cancelled, because the destination is not safe.
          [T]&2✔ Teleport anyways: &e/{cmd} &8[CLICK][H]&7Warning: The teleportation destination is not safe and might be dangerous for you.[/H][C]{cmd}[/C][/T]
      corrected: '&7The original teleport destination was unsafe. &7Your final destination
        has been corrected to a safe location.'
    claimblock:
      dropped: '&cSome claimblocks lie on the ground. &7There was no space left in
        your inventory.'
      success: '&7You got&3 {blocks} &7claimblock(s). &7Place them in a chunk to claim
        it.'
    capture:
      dropped: '&cSome capture flags lie on the ground. &7There was no space left
        in your inventory.'
      success: '&7You got&3 {blocks} &7capture flag(s). &7Place them into enemy claims
        during the war to start capturing an area.'
    camp:
      dropped: '&cSome camp items lie on the ground. &7There was no space left in
        your inventory.'
      success: '&7You got&3 {blocks} &7camp item(s). &7Place them to create a camp
        at the position.'
    blacklist:
      untrusted: '&cYou''re not allowed to use this command here. &7You''re not trusted
        in the area&6 {area} &7of land&2 {land}&7. &8Bypass permission: {permission}'
      general: '&cYou''re not allowed to use this command in claimed lands. &8Bypass
        permission: {permission}'
      war: '&cYou''re not allowed to use this command while you''re engaged in a war.
        &8Bypass permission: {permission}'
    auto-action:
      started:
        claim: '#t#&6Auto Claim[newline]&7Keep walking to claim chunks'
        unclaim: '#t#&6Auto Unclaim[newline]&7Keep walking to unclaim chunks'
      stopped:
        claim: '#t#&6Auto Claim[newline]&cStopped'
        unclaim: '#t#&6Auto Unclaim[newline]&cStopped'
    role:
      exists: '&cA role with the name&4 {role} &calready exists. &7Please choose a
        different name.'
      not-exist: '&cThe role&4 {role} &cdoes not exist in area &4{area} &cof land&4
        {land}&c. &7Typo?'
      max: '&cYou can''t create more roles for this land. &7You reached your limit
        of&3 {max} &7roles. Permission: lands.roles.<number>'
      player:
        land: '&cYou can''t edit this player in the land&4 {land}&c. &7Their role&6
          {role} &7has a higher or equal priority than yours.'
        area: '&cYou can''t edit this player in this area (&cArea:&4 {area} &cLand:&4
          {land}&c). &7Their role&6 {role} &7has a higher or equal priority than yours.'
      weight:
        land: '&cYou can''t edit the role&4 {role} &cof land&4 {land}&c. &7The roles
          priority is higher or equal than yours.'
        area: '&cYou can''t edit the role&4 {role} &cin this area (&cArea:&4 {area}
          &cLand:&4 {land}&c). &7The roles priority is higher or equal than yours.'
      delete:
        role: '&cYou can''t delete the role&4 {role}&c. &7This role is required.'
        entry: '&cYou can''t delete the entry role&4 {role}&c. &7It is required for
          new players.'
        visitor: '&cYou can''t delete the untrusted role&4 {role}&c. &7It is required
          for players that are not trusted.'
    
    chat-input:
      player: '#t#&6Enter the Name[newline]&7of the player in chat[newline]&7Enter
        "cancel" to abort.'
      object: '#t#&6Enter the Name[newline]&7of a land or nation in chat[newline]&7Enter
        "cancel" to abort.'
      land: '#t#&6Enter the Name[newline]&7of the target land in chat[newline]&7Enter
        "cancel" to abort.'
      title: '#t#&6Enter new Title[newline]&7for this land in chat[newline]&7Enter
        "cancel" to abort.'
      rename: '#t#&6Enter a new Name[newline]&7in chat[newline]&7Spaces are not allowed.
        Enter "cancel" to abort.'
      name: '#t#&6Enter the Name[newline]&7in chat[newline]&7Enter "cancel" to abort.'
      text: '#t#&6Enter the Text[newline]&7in chat[newline]&7Enter "cancel" to abort.'
  command:
    menu:
      invalid: '&cThere is no such shortcut with the name&4 {shortcut}&c.'
    rent:
      max-amount: '&cYou can''t rent or buy another area in the land&4 {land}&c. &7You
        already rented or bought the maximum amount of&3 {max} &7areas in this land.'
      own: '&cYou can''t rent / purchase your own offers. &7To remove a offer destroy
        the sign or shift + click at the hologram.'
      edit: '&cYou currently can''t edit area&4 {area} &cof land&4 {land}&7, because
        it''s rented/sold to player&3 {player}&7.'
      tenant: '&cYou haven''t rented the area at your current position. &7Area&6 {area}
        &7of land&2 {land} &7is not rented by you.'
      none: '&cThe area&4 {area} &cof land&4 {land} &cat your current position is
        not rented or bought by anyone.'
      status: '&cThe area&4 {area} &cof land&4 {land} &cat your current position is
        not set for rent or sale.'
      sign: |
        &7You need to specify a sign type (2. line)
         &81. line:&7 Lands
         &82. line:&3 rent &7or &3sell &8[&7area&8]
      set:
        land: '&cYou can''t set the whole land&4 {land} &cfor rent. &7You can either
          create subareas to set them for rent or you sell it completely (second line:
          sell).'
        already: '&cYou currently can''t set this area for rent again. &7The area&6
          {area} &7is currently being rented by&3 {player}&7. It will expire in&5
          {time}&7.'
        sold: '&cYou can''t set a area, which has been sold, for rent. &7The area&6
          {area} &7has been bought by player&3 {player}&7.'
        success: |
          &7You set area&6 {area} &7for rent. The tenant will pay&c {cost} &7each&5 {time}&7.
            [T]&8✖ &7Remove offer: &e/{cmd} &8[CLICK][H]&7Click here to remove the rental offer.[/H][C]{cmd}[/C][/T]
        invalid: |
          &7Your line format is invalid ({line}. line)
           &81. line:&7 Lands
           &82. line:&7 rent &8[&7area&8]
           &83. line:&7 TIME maxTime (not required)
           &84. line:&7 costs (example: 5 = 5)
        info: |
          [NoPrefix]
          &7&m━━━━━━━━━<━&r &5&lRent Area &7&m━>━━━━━━━━━
          [T]&8• &7Land:&a {land} &8[&8CLICK&8][H]&7Click here to visualize this area.[/H][C]lands view here[/C][/T]
           &8• &7Area:&6 {area}
           &8• &7Cost:&c {cost} &7each {time}
           &8• &8Max time: {max}
          &7&m━━━━━━━━━<━&r &5&lRent Area &7&m━>━━━━━━━━━
      rent:
        expire: '&cYou can''t add any more time to your rental of area&4 {area}&c.
          &7The land&2 {land} &7removed it for rental. It will expire in&5 {time}&7.'
        time: '&cYou can''t add any more time to your rental of area&4 {area}&c. &7The
          land&2 {land} &7configured a maximum of&5 {max} &7in total.'
        add: '&7You added&5 {add} &7to your rental of area&6 {area} &7for&c {cost}&7.
          It will expire in&5 {time}&7.'
        success: |
          &7You rented area&6 {area} &7of land&2 {land} &7for&c {cost}&7. It will expire in&5 {time}&7.
            &8✖ &7Adding more time: Click on the sign or hologram
            [T]&8✖ &7Cancelling rental: &e/{cmd} &8[CLICK][H]&7Click here to cancelling your rental.[/H][C]{cmd}[/C][/T]
        info: |
          [NoPrefix]
          &7&m━━━━━━━━━<━&r &5&lRented Info &7&m━>━━━━━━━━━
          [T]&8• &7Land:&a {land} &8[&8CLICK&8][H]&7Click here to visualize this area.[/H][C]lands view here[/C][/T]
           &8• &7Area:&6 {area}
           &8• &7Tenant: {player}
           &8• &7Time left:&5 {left}
           &8• &8Rent: {cost} each {time}
          &7&m━━━━━━━━━<━&r &5&lRented Info &7&m━>━━━━━━━━━
      cancel:
        success: '&7You cancelled the rental of area&6 {area}&7. You no longer have
          access to this area.'
      remove:
        offer:
          success:
            land: '&7Land&2 {land} &7is no longer able to be purchased.'
            area: '&7Area&6 {area} &7of land&2 {land} &7is no longer able to be rented
              or purchased. Existing tenants will stay until their rent time expires.'
        tenant:
          confirm: |
            &cPlease confirm that you want to pay&4 {cost} &cas compensation to the tenant&4 {player} &cin order to remove them:
              [T]&2✔ Confirm: &e/{cmd} &8[CLICK][H]&7Click here to confirm this action and payment.[/H][C]{cmd}[/C][/T]
          success: '&7You removed the tenant&3 {player} &7from area&6 {area} &7of
            land&2 {land} &7and paid&c {cost} &7as compensation.'
          target: '&cYou''ve been removed as a tenant from the area&4 {area} &4of
            land&4 {land}&c. &7They paid&c {compensation} &7as compensation to you.'
    sell:
      sell:
        rented: '&cYou can''t sell a area, which is being rented by a player. &7The
          area&6 {area} &7is currently being rented by&3 {player}&7. It will expire
          in&5 {time}&7.'
        success:
          area: |
            &7You set area&6 {area} &7for sale. Cost:&c {cost}
             &8✖ &7Remove offer: &e/lands rent removeoffer
          land: |
            &7You set the whole land&2 {land} &7for sale. Cost:&c {cost}
             &8✖ &7Remove offer: &e/lands rent removeoffer
        invalid: |
          &7Your line format is invalid ({line}. line)
           &81. line:&7 Lands
           &82. line:&7 sell &8[&7area&8]
           &83. line:&7 costs (example: 5 = 5)
      buy:
        owner-cooldown: '&cThe owner of a land can change every&4 {cooldown}&c. &7You
          must wait another&5 {time} &7before the land&2 {land} &7can be purchased.'
        success:
          area: '&7You bought area&6 {area} &7of land&2 {land} &7for&c {cost}&7.'
          land: '&7You bought the land&2 {land} &7for&c {cost}&7.'
        info:
          area: |
            [NoPrefix]
            &7&m━━━━━━━━━<━&r &5&lBuy Area &7&m━>━━━━━━━━━
            [T]&7Land:&a {land} &8[&8CLICK&8][H]&7Click here to visualize this area.[/H][C]lands view here[/C][/T]
             &7Area:&6 {area}
             &7Cost:&c {cost}
            &7&m━━━━━━━━━<━&r &5&lBuy Area &7&m━>━━━━━━━━━
          land: |
            [NoPrefix]
            &7&m━━━━━━━━━<━&r &5&lBuy Land &7&m━>━━━━━━━━━
            [T]&7Land:&a {land} &8[&8CLICK&8][H]&7Click here to visualize this land.[/H][C]lands view[/C][/T]
            &7Cost:&c {cost}
            &7&m━━━━━━━━━<━&r &5&lBuy Land &7&m━>━━━━━━━━━
      sold: |
        [NoPrefix]
        &7---------<- &5&lArea Sold &7->---------
        [T]&7Land:&a {land} &8[&8CLICK&8][H]&7Click here to visualize this area.[/H][C]lands view here[/C][/T]
         &7Area:&6 {area}
         &7Sold to&3 {player} &7for&c {cost}&7.
        &7---------<- &5&lArea Sold &7->---------
    general:
      no-permission: '&cYou don''t have permission to do this. &8You need permission
        {permission}.'
      not-exist: '&cThere is no such land or nation with the name&4 {object}&c. &7Typo?'
      land-not-exist: '&cThe land&2 {land} &cdoesn''t exist. &7There''s no land with
        this name.'
      area-not-exist: '&cArea&4 {area} &cdoes not exist in land&4 {land}&c. &7You
        can create a new area in your land menu in the areas section. &7Typo?'
      noaccess:
        untrusted: '&cYou''re not trusted in land&4 {land}&c. &7Use &e/lands menu
          &7to see the lands you''re a member of.'
        land: '&cYou''re not allowed to do this for this land&4 {land}&c. &8Flag:
          {flag}'
        owner: '&cYou''re not allowed to do this for the land&4 {land}&c. &7Only the
          land owner can do this. &7Select your own land &8(/&elands edit &8<&eland&8>)
          &7or create one &8(/&elands create &8<&ename&8>)&7.'
        area: '&cYou''re not allowed to do this in the area&4 {area} &cof land&4 {land}&c.'
        position:
          flag: '&cYou''re not allowed to do this for the land&4 {land} &cat your
            current position. &8Flag: {flag}'
          untrusted: '&cYou''re not allowed to do this for the land&4 {land} &cat
            your current position. &7You''re not trusted in this land.'
      no-edit-land: '&cYou haven''t selected your edit land yet. &7Use &e/lands edit
        &8<&eland&8> &7to select it.'
      name-exists: '&cThe name&4 {name} &cis already taken by another land or nation.
        &7You need to choose a different one.'
      swear-word: '&cDetected a swear word. &7Please do not use mature language. Word:&c
        {word}'
      action-cooldown: '&cYou can''t do this now. &7You need to wait&5 {time}&7.'
      wilderness: '&cThere''s no claimed land at your current position. &7Please go
        into your land first, in order to execute this action. &7You can use &e/view
        &7to visualize claims around you.'
      player-self: '&cYou can''t do that with yourself.'
      banks-disabled: '&7Banks were disabled by an administrator. &8They can enable
        it in the config.'
      land-not-trusted: '&cPlayer&4 {player} &7isn''t part of the land&4 {land}&c.
        You need to trust him first using &e/lands trust&7.'
      area-not-trusted: '&cYou can''t do that here. &7You''re not trusted in area&6
        {area} &7of land&2 {land}&7.'
      number: '&cYour input&4 {input} &cisn''t a number. &7The argument&3 {argument}
        &7needs to be a number.'
      none: |
        &cYou're not a member of any land.
          [T]&8✖ &7Create your own: &e/{cmd} &8[CLICK][H]&7Click to copy.[/H][SC]{cmd}[/SC][/T]
             &7Any land can invite you using: &e/lands trust
      name:
        number: '&cYou''re not allowed to use numbers for this name. &7Please use
          only letters. Found number:&3 {invalid}'
        character: '&cYou can''t use invalid characters for the name. &7Please use
          only letters and numbers. &7Found invalid character:&3 {invalid}'
        color: '&cYou''re not allowed to use color codes for this name. &7Please remove
          any color codes from your input.'
        length: '&cThis name is too long. &7Max length is&3 {max} &7characters &8(&7yours:
          {input}&8)&7. &8This includes color codes. &7Please provide a shorter name.'
        empty: '&cThis name is invalid. &7You need to enter at least one character
          other than color codes.'
      money:
        fallback: '&7Notice:&c {cost} &7has been taken from your personal account,
          because the bank of your land&2 {land} &7does not have enough money inside
          it. Deposit: &e/{cmd}[T]&8[CLICK][H]&7Click here to deposit money into the
          bank of land {land}.[/H][SC]{cmd}[/SC][/T]'
        failure:
          bank: '&cYou don''t have enough to pay the cost. &7You need&c {cost}&7.
            Deposit money into your land bank: [T]&e/{cmd} &8[CLICK][H]&7Click here
            to deposit {cost} into your land bank.[/H][C]{cmd}[/C][/T]'
          personal: '&cYou don''t have enough to pay the cost. &7You need&c {cost}&7.
            Your balance: {balance}'
      input:
        confirm: |
          &7Please confirm this action &8(&e/{input}&8) &7by clicking below:
            [T]&2✔ Confirm: &e/{fullcmd} &8[CLICK][H]&7Click here to confirm this action.[/H][C]{fullcmd}[/C][/T]
        land: '&cThe land&4 {input} &cdoesn''t exist. &7There''s no land with this
          name.'
        nation: '&cThe nation&4 {input} &cdoesn''t exist. &7There''s no nation with
          this name.'
        holder: '&cThere is not such land or nation with the name&4 {input}&c. &7Typo?'
        number: '&cYour input&4 {input} &cisn''t a number. &7Argument {pos}: {expected}'
        category: '&cYour input&4 {input} &cisn''t a category. &7Argument {pos}: {expected}'
        funds: '&cYour input&4 {input} &cdoesn''t match any currency. &7Argument {pos}:
          {expected}'
        player: '&cThere''s no player with the name&4 {input}&c. &7Typo?'
        offline: '&cThere''s currently no player with the name&4 {input} &conline.
          &7Typo?'
        world: '&cThe world&4 {input} &cdoesn''t exist. &7Argument {pos}: {expected}'
        world-disabled: '&cThis is deactivated in this world. &8World: {input}'
        time: '&cYour input&4 {input} &cdoesn''t represent time. &7Argument {pos}:
          {expected}. Correct example: 1h'
    create:
      land-other: '&cYou''re not allowed to have your own land and be a member of
        another land. &7You need to leave land&2 {land} &7first.'
      max:
        land: '&cYou can''t create any more lands. &7You reached your maximum of&3
          {max} &7own lands.'
        camp: '&cYou can''t create any more camps. &7You reached your maximum of&3
          {max} &7camps.'
      success:
        land: |
          &7Successfully created land&2 {land} &7for&c {cost}&7.
          Set land {land} &7as your edit land for future actions.
            [T]&7✖ Change edit land: &3/{cmd_edit} &8[CLICK][SC]{cmd_edit}[/SC][H]&7Land {land} has been set as your edit land for actions like trusting players etc. To change that execute this command. Click to copy.[/H][/T]
            [T]&7✖ Claim chunk: &3/{cmd_claim} &8[CLICK][C]{cmd_claim}[/C][H]&7Click here to claim the chunk you're standing in.[/H][/T]
            [T]&7✖ Claim selection: &3/{cmd_selection} &8[CLICK][C]{cmd_selection}[/C][H]&7Click here to claim a selection of chunks.[/H][/T]
            [T]&7✖ Trust players: &3/{cmd_trust} &8[CLICK][SC]{cmd_trust}[/SC][H]&7Click to copy.[/H][/T]
        camp: '&7You created the camp&2 {land} &7at your current position. &7You paid&c
          {cost}&7. The camp can''t be expanded and will expire in&5 {time}&7.'
      broadcast: '&7Land&2 {land} &7was created by&3 {player}&7.'
    rename:
      success: '&7Successfully set the new name&3 {name} &7for the land&2 {land}&7.
        You paid&c {cost}&7.'
    edit:
      success: '&7You entered the edit mode for the land&2 {land}&7. Next actions,
        like &e/lands claim &7or &e/lands trust&7, will be executed for this land.'
    selection:
      max: '&cYour selection has too many chunks in it. &7Size:&3 {current} &7Your
        maximum size is&3 {max} &7chunks.'
      too-far: '&cThe block you''re looking at is too far away. &7Please move closer
        to it.'
      world: '&cBoth positions must be in the same world. &7Please set position one
        and position two in the same world.'
      pos:
        warn: '&cWarning: &7This chunk belongs to another management plugin. Name:&3
          {plugin}'
        cancelled: '&cYou can''t set a selection here. &7This chunk belongs to another
          management plugin. Name:&3 {plugin}'
      area:
        conflicts: '&cFound&4 {conflicts} &cconflict(s) with chunks already assigned
          to area(s). &7Use &e/lands selection assign {area} confirm &7to confirm
          the override. Conflicts belong to these areas: {areas}'
      expand:
        y: '&7Expanded the selection''s lowest point by&3 {y-min} &7and the highest
          point by&3 {y-max}&7.'
        enabled: '&7Expanded your selection from bottom to the top (min and max claim
          height).'
        disabled: '&7Your selection isn''t any longer expanded from bottom to the
          top.'
      status:
        complete: '#t#&6Selection Complete[newline]&7Claim: &e&l/claim &7Unclaim:
          &e&l/unclaim[newline]&6&lAssign selection to a subarea: &e&l/assign'
        progress: '#t#&6Selection[newline]&7Left: {first} &7Right: {second}[newline]&6&lSet
          corner: &6left/right click or drop item &7&lCancel: &7Change tool slot'
        reminder: |
          &7Selection is complete: Following actions can be executed:
            [T]&7✖ Claim: &e/claim &8[&8CLICK&8][H]&7Click here to claim this selection.[/H][C]lands claim[/C][/T]
            [T]&7✖ Unclaim: &e/unclaim &8[&8CLICK&8][H]&7Click here to unclaim this selection.[/H][C]lands unclaim[/C][/T]
            [T]&7✖ Subarea: &e/assign &8[&8CLICK&8][H]&7Assign this selection to a subarea.[/H][SC]lands assign <area>[/SC][/T]
        not-complete: '&cYour selection is not complete. &7Please make sure that both
          positions are set. [T]&7You can toggle the selection mode by executing &e/lands
          selection &8[&8CLICK&8][H]&7Click here to toggle the selection mode.[/H][C]lands
          selection[/C][/T]'
        disabled: '#t#&6Selection[newline]&cMode disabled'
    claim:
      camp: |
        &cYour camp&4 {land} &ccan't be expanded.
          [T]&7✖ Change land: &e/lands edit &8<&eland&8> &8[&8CLICK&8][SC]lands edit[/SC][H]&7Click to copy this command.[/H][/T]
      create:
        auto: |
          &7Automatically created a new land&2 {land}&7, because you didn't have one for which you could claim.
            [T]&7✖ Rename: &e/lands rename &8<&ename&8> &8[&8CLICK&8][SC]lands rename[/SC][H]&7Click to copy this command.[/H][/T]
        force_near: |
          &7Automatically created a new land&2 {land}&7, because your previous one wouldn't be connected to this claim.
            [T]&7✖ Rename: &e/lands rename &8<&ename&8> &8[&8CLICK&8][SC]lands rename[/SC][H]&7Click to copy this command.[/H][/T]
      region:
        chunk: '&cYou can''t claim land here. &7This chunk already belongs to another
          region management plugin: {plugin}'
        selection: '&cYou can''t claim this selection. &7It contains parts of a region
          from another region management plugin: {plugin}'
      war: '&cYou can''t claim while being engaged in a war against {object}&c.'
      already: '&cYou can''t claim this chunk. &7It already belongs to land&2 {land}&7.'
      initial-world: '&cFor land&4 {land} &cyou can only claim in its initial land
        creation world&4 {world}&c. &7You may want to create another land for the
        world you''re currently in ({current}): &e/lands create &8<&ename&8>'
      near-other: '&cThis is too near to land&4 {land}&c. &7You need to move further
        away from this land. Minimum chunk distance is&3 {distance}&7.'
      force-near:
        far-land: '&cYou can''t claim this chunk(s). &7Your claims need to be connected
          to your land&2 {land}&7.'
        parts: '&cYou can''t claim this chunk(s). &7Your claims need to be connected
          to your land&2 {land}&7, because it reached its limit of &c{max} &7disconnected
          parts.'
      success: '&7Successfully claimed this chunk &8(&7Land:&2 {land} &7X: {x} Z:
        {z}&8) &7for&c {cost}&7. Next claim will cost&c {next}&7.'
      already-claimed: '&cIn your selection is a chunk that is already claimed and
        does not belong to your land &8(&7X: {x} Z: {z}&8)&c. &7It belongs to land&2
        {land}&7.'
      max-chunk: '&cYou can''t claim&4 {chunks} &cmore chunks for this land. &7The
        maximum for land&2 {land} &7is&3 {max} &7chunks. &8Permission: lands.chunks.<number>'
      processing: '&cThere is already a selection being processed. &7Please wait until
        it completes.'
      selection:
        success: '&7You successfully claimed&3 {chunks} &7chunks for your land&2 {land}&7.
          You paid&c {cost}&7.'
      radius:
        success: '&7You successfully claimed&3 {chunks} &7chunks in the radius of&7
          {radius} &7chunks around you for your land&2 {land}&7. You paid&c {cost}&7.'
      fill:
        none: '&cCouldn''t find shape. &7Please make sure you stand in an unclaimed
          region that is surrunded by your claim.'
        success: '&7You successfully claimed&3 {chunks} &7chunks for your land&2 {land}
          &7in order to fill the shape you stood in. You paid&c {cost}&7.'
    merge:
      confirm: |
        &7Please confirm that you want to merge land&2 {merge} &7into&2 {land}&7:
          [T]&2✔ Confirm: &e/{fullcmd} &8[CLICK][H]&7Click here to confirm this action.[/H][C]{fullcmd}[/C][/T]
      same: '&cYou can''t merge land&4 {merge} &cinto itself. &7Please specify a different
        land.'
      max:
        chunks: '&cYou can''t merge land&4 {merge} &cinto&4 {land}&c. &7Their total
          amount of&3 {chunks} &7chunks exceeds the limit of&3 {max} &7chunks for
          your land&2 {land}&7.'
      connection: '&cYou can''t merge land&4 {merge} &cinto&4 {land}&c. &7Their claims
        aren''t connected in world&3 {world}&7.'
      nation: |
        &cYou can't merge land&4 {merge} &cinto&4 {land}&c. &7Land&2 {merge} &7is the capital of nation&9 {nation}&7.
          [T]&7✖ Change capital: &e/nations setcapital &8<&eland&8>[H]&7Click here to change the nations capital. This will allow you to merge land {merge}. Click to copy.[/H][SC]nations setcapital[/SC][/T]
      success: '&7You successfully merged land&2 {merge} &7into&2 {land}&7. You paid&c
        {cost}&7.'
    assign:
      selection: '&cYou need to create a selection first. &7Use &e/lands selection
        &7to create one. After that try again.'
      default: '&cYou can''t assign the selection to a default area. &7Areas can be
        deleted in the areas menu of the land.'
      confirm: |
        &cYour selection has a low height. &7Sub areas, unlike claims, have a height and do not extend from the bottom to the top by default.
          [T] &7✖ Proceed: &e/{cmd_confirm} &8[CLICK][H]&7Click here to proceed.[/H][C]{cmd_confirm}[/C][/T]
          [T] &7✖ Expand fully: &e/{cmd_expand} &8[CLICK][H]&7Click here to expand the selection from the bottom to the top of the claim.[/H][C]{cmd_expand}[/C][/T]
      size: '&cYour selection is too small. &7The minimum size is&3 {min} &7blocks
        and yours is&3 {current}&7.'
      success: '&7You successfully resized the area&6 {area} &7of land&2 {land}&7.
        Changes are visualized.'
      conflict:
        land: '&cYour selection conflicts with land&4 {land}&c. &7Please adjust your
          selection.'
        area: '&cYour selection conflicts with area&4 {area}&c. &7Please adjust your
          selection.'
    leave:
      owner: |
        &cYou can't leave this land. &7As the owner of a land you can delete the land or just transfer the ownership.
          [T]&c✘ Delete &8[&8CLICK&8][C]lands delete[/C][H]&7Click to delete land&2 {land}&7.[/H][/T]
          [T]&2✔ Transfer ownership &8[&8CLICK&8][SC]lands setowner [/SC][H]&7Click to copy this command.[/H][/T]
      land:
        untrusted: '&7You aren''t trusted in any areas of land&2 {land}&7.'
        success: '&7Successfully left the whole land&2 {land}&7.'
      area:
        untrusted: '&7You aren''t trusted in area&6 {area} &7of the land&2 {land}&7.'
        success: '&7Successfully left the area&6 {area} &7of the land&2 {land}&7.'
    unclaim:
      rental: '&cYou can''t unclaim this chunk&7, because it contains the rented or
        sold area&6 {area}&7. Remove the tenant&3 {player}&7: &e/{cmd}'
      split: '&cYou can''t unclaim this chunk, because this would cause your land
        to split up into parts. &7Parts that would split up are now visualized.'
      success: '&7Successfully unclaimed this chunk &8(&7Land:&2 {land} &7X: {x} Z:
        {z}&8)&7. You got&c {back} &7back.'
      all:
        success: '&7You successfully unclaimed all chunks for land&2 {land} &7and
          got&3 {back} &7back.'
        confirm: |
          &7Please confirm that you want to unclaim all claims of land&2 {land}&7:
            [T]&2✔ Confirm: &e/{fullcmd} &8[CLICK][H]&7Click here to confirm this action.[/H][C]{fullcmd}[/C][/T]
      selection:
        empty: '&cYou did not unclaim any chunks, because they are not claimed or
          you''re not allowed to unclaim any of them.'
        rental: '&cYou can''t unclaim this selection&7, because it contains the rented
          or sold area&6 {area} &7of land&2 {land}&7. Remove the tenant&3 {player}&7:
          &e/{cmd}'
        split: '&7You unclaimed {success} / {size} chunks of this selection, &cbut
          {failed} could not be unclaimed because it would result in your land being
          split up into parts &8(a admin can disable this in config)&7. Parts that
          would split up are now visualized. You got&c {back} &7back.'
        partly: '&7You successfully unclaimed {success} / {size} chunks of this selection.
          You got&c {back} &7back.'
        success: '&7You successfully unclaimed all chunks of this selection. You got&c
          {back} &7back.'
    delete:
      confirm: |
        &7Please confirm the deletion of land&2 {land} &7by clicking below:
          [T]&2✔ Confirm: &e/{fullcmd} &8[CLICK][H]&7Click here to confirm this action.[/H][C]{fullcmd}[/C][/T]
      nation: '&cYou can''t delete this land, because it''s the capital of nation&4
        {nation}&c. &7You need to delete the nation first: &e/nations delete'
      success: '&7Successfully deleted your land&2 {land}&7. You got&e {back} &7back.'
      rented: '&cYou can''t delete this land, because its area&4 {area} &cis rented
        or bought by&4 {player}&c. [T]&7To remove the tenant, execute &e/{cmd} &8[CLICK]
        &7while standing in that area.[H]&7Click here to remove the tenant.[/H][C]{cmd}[/C][/T]'
      broadcast: '&7The land&2 {land} &7was deleted by&3 {player}&7.'
    trust:
      own-land: '&cPlayer&4 {player} &ccan''t be invited to join another land. &7They''re
        not allowed to have their own land and be a member of another land at the
        same time. They need to delete their own land&2 {land} &7first.'
      max-lands: '&7Player&3 {player} &7has already reached the maximum amount of
        lands. &8Permission: lands.lands.<number>'
      max-members: '&cCouldn''t trust player&4 {player} &cin land&4 {land}&c. &7Your
        land&2 {land} &7reached its maximum of&3 {members} &7members in their land.'
      max: '&cThe player&4 {player} &ccan''t join any more lands. &7They reached their
        maximum of&3 {max} &7lands to join. &8Permission: lands.lands.<number>'
      flag: '&cThe player&4 {player}&c doesn''t want to receive invites from any land.
        &7They can change this in their menu, by executing &8/&3{cmd}&7.'
      area:
        invited: '&cThe player&4 {player} &cis already invited to the area&4 {area}
          &cof land&4 {land}&c. &7The invite has been sent&5 {time} &7ago.'
        trusted: '&7The player&3 {player} &7is already trusted in the area&6 {area}
          &7of land&2 {land}&7.'
        banned: |
          &cYou can't trust player&4 {player}&c to the area&4 {area}&c of land&4 {land}&c. &7They're banned.
            [T]&2✔ Unban: &e/{cmd} &8[&8CLICK&8][H]&7Click here to unban this player.[/H][C]{cmd}[/C][/T]
        success: '&7Successfully invited player&3 {player} &7to the area&6 {area}
          &7of land&2 {land}&7. They can now accept your invite.'
        target: |
          [T]&7Player&3 {player} &7invited you to join the area&6 {area} &7of their land&2 {land}&7.[H]&7Click to open your invites menu.[/H][C]lands invites[/C][/T] &7Taxes:&c {tax}
            [T]&2✔ Accept: &e/{cmd_accept} &8[&8CLICK&8][H]&7Click here to accept this invite.[/H][C]{cmd_accept}[/C][/T]
            [T]&c✘ Deny: &e/{cmd_accept} &8[&8CLICK&8][H]&7Click here to deny this invite.[/H][C]{cmd_deny}[/C][/T]
      land:
        invited: '&cThe player&4 {player} &cis already invited to the whole land&4
          {land}&c. &7The invite has been sent&5 {time} &7ago.'
        trusted: '&7The player&3 {player} &7is already trusted in land&2 {land}&7.'
        banned: |
          &cYou can't trust player&4 {player}&c in the land&4 {land}&c. &7They're banned in the whole land.
            [T]&2✔ Unban: &e/{cmd} &8[&8CLICK&8][H]&7Click here to unban this player from the whole land.[/H][C]{cmd}[/C][/T]
        success: '&7Successfully invited player&3 {player} &7to the the whole land&2
          {land}&7. They now can accept your invite.'
        target: |
          [T]&7Player&3 {player} &7invited you to join their land&2 {land}&7.[H]&7Click to open your invites menu.[/H][C]{cmd_invites}[/C][/T] &7Taxes:&c {tax}
            [T]&2✔ Accept: &e/{cmd_accept} &8[&8CLICK&8][H]&7Click here to accept this invite.[/H][C]{cmd_accept}[/C][/T]
            [T]&c✘ Deny: &e/{cmd_deny} &8[&8CLICK&8][H]&7Click here to deny this invite.[/H][C]{cmd_deny}[/C][/T]
    untrust:
      owner: '&cLand owners can''t be untrusted. [T]&7New owners can be set using
        &e/{cmd}&7. &8[CLICK][H]&7Click here to copy this command.[/H][SC]{cmd}[/SC][/T]'
      area:
        already: '&7The player&3 {player} &7isn''t trusted in this area &8(&7Area:&6
          {area} &7Land:&2 {land}&8) &7and hasn''t received a invite previously.'
        revoke: '&7Successfully revoked the invite for player&3 {player} &7in this
          area &8(&7Area:&6 {area} &7Land:&2 {land}&8)&7. The player isn''t trusted.'
        success: '&7Successfully untrusted player&3 {player} &7in this area &8(&7Area:&6
          {area} &7Land:&2 {land}&8)&7.'
        rental: '&cYou can''t untrust the tenant&4 {player} &cof area&4 {area}&c.
          &7To remove the area for rental, use &e/lands rent remove &7while standing
          on the area.'
      land:
        already: '&7The player&3 {player} &7isn''t trusted in any areas of the land&2
          {land} &7and hasn''t received any invites.'
        revoke: '&7Successfully revoked the invite for player&3 {player} &7for the
          whole land&2 {land}&7. The player isn''t trusted in any areas.'
        success: '&7Successfully untrusted player&3 {player} &7in the whole land&2
          {land}&7, except for areas which they rented/bought.'
    setrole:
      visitor: '&cYou can''t set the&4 {role} &crole. &7If you want to untrust this
        player, please use &e/lands untrust {player} [area]&7.'
      land:
        untrusted: '&cThe player&4 {player} &cisn''t trusted in the land&4 {land}&c.
          &7Please trust them first.'
        success: '&7Successfully set role&3 {role} &7for player&3 {player} &7in areas
          of land&2 {land}&7, in which they''re trusted.'
      area:
        untrusted: '&cThe player&4 {player} &cisn''t trusted in the area&4 {area}
          &cof land&4 {land}&c. &7Please trust them first.'
        success: '&7Successfully set role&3 {role} &7for player&3 {player} &7in the
          area&6 {area} &7of land&2 {land}&7.'
    accept:
      max: '&cYou can''t be part of any more lands. &7You reached your maximum of&3
        {max} &7lands. &8Permission: lands.lands.<number>'
      not-exist: '&cYou don''t have an invite from land&4 {land} &cor it expired.
        &7Please check your input.'
      own-land: '&cYou can''t join another land. &7You''re not allowed to have your
        own land and be a member of another land at the same time. &7You need to delete
        your own land&2 {land} &7first.'
      max-lands: '&cYou can''t join any more lands. &7You can only have&3 {max} &7lands.
        &8Permission: lands.lands.<number>'
      banned: '&cYou can''t join area&4 {area}&7 of land&4 {land}&c. &7They''ve banned
        you from this area.'
      max-members: '&cYou currently can''t join land&4 {land}&c. &7They reached their
        maximum of&3 {members} &7members in their land.'
      war: '&cYou currently can''t join land&4 {land}&c, because it is engaged in
        a war against {object}&c. &7Try again when their war is over.'
      notification: "&7You have&3 {invites} &7invites from other lands. \n\n [T]&7View\
        \ received: &e/{cmd} &8[CLICK][H]&7View all received invites from other lands.[/H][C]{cmd}[/C][/T]\n"
      area:
        success: '&7Successfully accepted invite from land&2 {land} &7for the area&6
          {area}&7.'
        broadcast: '&2{land} &8| &7Player&3 {player} &7is now a member of the area&6
          {area} &7in our land.'
      land:
        success: '&7Successfully accepted the invite from land&2 {land} &7to be trusted
          in the whole land.'
        owner: '&7You accepted the invite from land&2 {land}&7. You''re now the owner
          of land&2 {land}&7.'
        broadcast: '&2{land} &8| &7Player&3 {player} &7is now a member of our land.'
    setowner:
      confirm: |
        &7Please confirm that you want to set player {player} as the new owner of land&2 {land}&7:
          [T]&2✔ Confirm: &e/{fullcmd} &8[CLICK][H]&7Click here to confirm this action.[/H][C]{fullcmd}[/C][/T]
      max:
        ownlands: '&cThe player&4 {player} &cisn''t allowed to own any more lands.
          &7They already reached their maximum of&3 {max} &7own lands.'
        chunks: '&cThe player&4 {player} &ccan''t own this land. &7It has&3 {chunks}
          &7chunks, which exceeds their maximum amount of&4 {max} &7chunks for this
          land.'
      cooldown: '&cThe owner can only be changed every&4 {cooldown}&c. &7You must
        wait another&5 {time}&7.'
      success:
        invited: '&7You successfully invited player&3 {player} &7to become the new
          owner of land&2 {land}&7.'
        set: '&7You successfully set player&3 {player} &7as the new owner of land&2
          {land}&7.'
        target: |
          [T]&7Player&3 {player} &7invited you to become the new owner of land&2 {land}&7.[H]&7Click to open your invites menu.[/H][C]lands invites[/C][/T] &7Upkeep:&c {upkeep}
            [T]&2✔ Accept: &e/{cmd_accept} &8[&8CLICK&8][H]&7Click here to accept this invite.[/H][C]{cmd_accept}[/C][/T]
            [T]&c✘ Deny: &e/{cmd_deny} &8[&8CLICK&8][H]&7Click here to deny this invite.[/H][C]{cmd_deny}[/C][/T]
    deny:
      not-exist: '&cYou don''t have an invite from land&4 {land} &cor it expired.
        &7Typo?'
      success: '&7You successfully denied the invite from land&2 {land}&7.'
    teleport:
      chunk-not-claimed: '&cThe destination chunk isn''t claimed &8(&7X: {x} &7Z:
        {z}&8)&c.'
      not-trusted: '&cYou can''t teleport to this location. &7You''re not trusted
        in land&2 {land}&7.'
      success: '&7Successfully teleported to X:&3 {x} &7Z:&3 {z} &7Claimed: {claimed}'
    setspawn:
      wilderness: '&cYou can only set the land spawn in your land. &7You either need
        to move up or down into your land&2 {land}&7.'
      success: '#t#&6Spawnpoint set[newline]&7Cost:&c {cost}'
    spawn:
      not-exist: '&cThere''s no spawn set for land&4 {land}&c. &7Someone needs to
        set it first by executing &e/lands setspawn&7.'
      not-allowed: '&cYou''re not allowed to teleport to the spawn of land&4 {land}&c.
        &7They need to give you permission in their role settings to do so.'
      war: '&cYou currently can''t teleport to the spawn of land&4 {land}&c. &7They''re
        currently engaged in a war, that will end in&5 {time}&7.'
      chunk: '&7Land&2 {land} &7hasn''t set a land spawn &8(&e/lands setspawn&8) &7yet.
        &7Teleported you to the initial claim of this land.'
      success: '&7Successfully teleported to the spawn of land&2 {land} &7Cost:&c
        {cost}'
      area:
        cooldown: '&cYou can''t teleport to area spawns right now. &7You need to wait
          another &5{time} &7before you can teleport to an area again.'
        none: '&cThe area&4 {area} &cof land&4 {land} &cdoesn''t have an spawn set.'
        teleport: '&cYou''re not allowed to teleport to this area. &7The land owner
          can give you permission to do so.'
        enter: '&cYou''re not allowed to enter this area. &7The land owner can give
          you permission to do so.'
        success: '&7Successfully teleported to the spawn of area&6 {area} &7of land&2
          {land}&7.'
    wild:
      perm: '&cYou''re not allowed to use random teleportation in the world&4 {world}&c.
        &8You''re missing the permission {perm} for this world.'
      no-location: '&cCouldn''t find a safe location for you that matches the filter
        in config. &8Please adjust your max and min distance settings and set the
        world spawn (/setworldspawn).'
      searching: '#t#&6Searching[newline]&7Destination...'
      success: '&7You were randomly teleported &8(&7X: {x} Z: {z}&8)&7. You paid&c
        {cost}&7.'
    deposit:
      number: '&7You need to specify an amount of money. Use &e/lands deposit &8<&eamount&8>
        &7or &e/lands deposit &8<&eland&8> <&3amount&8>&7.'
      partly: '&cOnly deposited&4 {cost} &cof the provided&4 {input}&7, because the
        bank of land&2 {land} &7reached the maximum balance of&3 {max}&7.'
      success: '&7You successfully put&3 {cost} &7in the bank of land&2 {land}&7.
        &7New balance of the bank:&3 {bank}'
    withdraw:
      number: '&7You need to specify an amount of money. Use &e/lands withdraw &8<&eamount&8>
        &7or &e/lands withdraw &8<&eland&8> <&3amount&8>&7.'
      balance: '&cThere''s not enough money in the land bank of land&4 {land}&c. &7There''s
        only&3 {bank} &7available. Expected:&3 {take}'
      failed: '&cWithdraw failed. &7The server might limit the amount of funds you
        can withdraw.'
      success: '&7You successfully took&3 {cost} &7out of the bank of land&2 {land}&7.
        &7New balance of bank:&3 {bank}'
    balance: '&7The balance of land&2 {land} &7is&3 {balance}'
    ban:
      area:
        already: '&7Player&3 {player} &7is already banned in the area&6 {area} &7of
          land&2 {land}&7.'
        success: '&7Successfully banned player&3 {player} &7in the area&6 {area} &7of
          land&2 {land}&7. They won''t be able to enter it or teleport to the spawn,
          if it is located in this area.'
        target: '&cLand&4 {land} &cbanned you from their area&4 {area} &cinside their
          land. &7You won''t be able to enter it or teleport to the spawn, if it is
          located in this area.'
      land:
        already: '&7Player&3 {player} &7is already banned in the whole land&2 {land}&7.'
        success: '&7Successfully banned player&3 {player} &7from the whole land&2
          {land}&7. They won''t be able to enter any areas or teleport to the spawn.'
        tenant: '&cYou can''t ban the player&4 {player}&c from the whole land&4 {land}&c,
          because they''re the tenant of area&4 {area}&c. &7Remove tenant: &e/{cmd}'
        target: '&cLand&4 {land} &cbanned you from their whole land&c. &7You won''t
          be able to enter any areas of it or teleport to the spawn.'
    unban:
      area:
        success: '&7Successfully unbanned player&3 {player} &7from this area &8(&7Area:&6
          {area} &7Land:&2 {land}&8)&7.'
      land:
        success: '&7Successfully unbanned player&3 {player} &7from the land&2 {land}&7.'
    chat:
      activated: '&7Activated land chat. Send a message in public chat to chat with
        your land.'
      deactivated: '&7Successfully deactivated land chat.'
      none: "&cNo land found for land chat. \n  [T]&7✖ &7Disable chat mode: &e/{cmd}\
        \ &8[&8CLICK&8][H]&7Click here to deactivate the chat mode.[/H][C]{cmd}[/C][/T]\n"
      format:
        minecraft: '[NoPrefix]&2{land} &8| {role} &7{player} &8»&f {message}'
        discord: '[NoPrefix]&2{land} &8| &9Discord &7{player} &8»&f {message}'
        spy: '[NoPrefix]&8[&cChatSpy&8] &2{land} &8| {role} &7{player} &8»&f {message}'
    view:
      disabled: '&7You successfully disabled the current visualization.'
      wilderness: '&7Enabled visualization of claims. &7Your current position is wilderness.'
      tool: '&7The position you''re pointing at is wilderness. [T]&7Claim it: &e/{cmd}
        &8[CLICK][H]&7Click to claim the chunk you''re pointing at.[/H][C]{fullcmd}[/C][/T]'
      y-level: '&7The current position is wilderness, but the chunk is already claimed
        by land&2 {land} &7at a different y-level.'
      y-lock:
        enabled: '&cToggled y-lock mode: &7The land borders will no longer follow
          your position up and downwards.'
        disabled: '&aToggled y-lock mode: &7The land borders will follow your position
          up and downwards.'
      info: |
        [NoPrefix]
        &7&m━━━━━━━━━<━&r &5&lLand View &7&m━>━━━━━━━━━
        [T]&8• &7Land: &2{land} &8[&8CLICK&8][H]&7Click here to get more information about this land.[/H][C]{cmd}[/C][/T]
        &8• &7Level: {level}
        &8• &7Nation: {nation}
        &8• &7Chunk &7X: {x} Z: {z}
        &7&lArea:&6 {area}
         &8• &7Tax:&c {tax}
         &8• &7Players:&7 {players}
         &8• &7Description:&r {description}
        &7&m━━━━━━━━━<━&r &5&lLand View &7&m━>━━━━━━━━━
      area: |
        [NoPrefix]
        &7&m━━━━━━━━━<━&r &5&lArea View &7&m━>━━━━━━━━━
        [T]&8• &7Land: &2{land} &8[&8CLICK&8][H]&7Click here to get more information about this land.[/H][C]lands info {land}[/C][/T]
        &8• &7Level: {level}
        [T]&7&lArea:&6 {area} &8[&8CLICK&8][H]&7Click here to get more information about this area.[/H][C]lands menu here[/C][/T]
         &8• &7Tax:&c {tax}
         &8• &7Players:&7 {players}
         &8• &7Description:&r {description}
        &7&m━━━━━━━━━<━&r &5&lArea View &7&m━>━━━━━━━━━
    map:
      header: '&7&m━━━━━━━━━━<━&r &2Lands Map &7&m━>━━━━━━━━━━[newline]'
      footer: '[newline]&7&m━━━━━━━━━━<━&r &2Lands Map &7&m━>━━━━━━━━━━'
    unstuck:
      success: '&7Successfully teleported into the nearest unclaimed location.'
    taxes:
      none: '&7There aren''t any upcoming tax payments for you.'
      upcoming:
        header: '[NoPrefix]&7&m━━━━━━━━━<━&r &cUpcoming Taxes &7&m━>━━━━━━━━━'
        entry: '[NoPrefix]&8- &7{land}: &c{tax}'
        footer: |
          [NoPrefix]&7You need to pay a total of {total} in &5{next}&7.
          &7Balance: {balance}
          &7&m━━━━━━━━━<━&r &cUpcoming Taxes &7&m━>━━━━━━━━━
      changes:
        header: |
          [NoPrefix]
          &7&m━━━━━━━━━<━&r &4Tax Change &7&m━>━━━━━━━━━
          &cTaxes have been changed in some lands:
        entry: '[NoPrefix]&8- &7{land}: {color}{tax} &8(previously: {previous})'
        footer: |
          [NoPrefix]
          &7Payment in:&5 {next}
          &7Balance: {balance}
          &8More info: /lands taxes
          &7&m━━━━━━━━━<━&r &4Tax Change &7&m━>━━━━━━━━━
    upkeep:
      none: '&7You currently don''t have to pay upkeep for any land.'
      header: '[NoPrefix]&7&m━━━━━━━━━<━&r &cUpcoming Upkeep &7&m━>━━━━━━━━━'
      entry: '[NoPrefix][T]{covered} {land}: {upkeep_form} &8[CLICK][C]{cmd}[/C][H]&7Click
        here to deposit the required money.[/H][/T]'
      footer: |
        [NoPrefix]&7Your lands need to pay a total of {total} in &5{next} &7in order to keep up all claims or membership in their nation. &7Click above to deposit money into your land's banks.
        &7&m━━━━━━━━━<━&r &cUpcoming Upkeep &7&m━>━━━━━━━━━
    relations:
      self: '&cYou can''t add&4 {object} &cas an ally or enemy to itself.'
      nation: '&cAll relations are managed by the nation&4 {nation}&c, which your
        land is part of.'
      allies:
        add:
          already: '&7{target} &7is already an ally of {object}&7.'
          nation: |
            &cYou can't get into an alliance with land&4 {land}&c. &7The land is governed by nation&9 {nation}&7.
              [T]&7✖ Send Alliance request to nation&9 {nation} &7instead: &e/{cmd} &8[CLICK][H]&7Click here to send an alliance request to nation&9 {nation}&7.[/H][C]{cmd}[/C][/T]
          success: '&7Successfully sent an ally offer to {target}&7. If they accept
            it, you &8(&7{object}&8) &7will be allied with them.'
        remove:
          already: '&7{target} &7isn''t an ally of {object}&7.'
          revoked: '&7You &8(&7{object}&8) revoked the ally offer for {target}&7.'
          broadcast: '&7{object} &7and {target} &7are no longer allies.'
          success: '&7Successfully removed {target}&7 from your allies. You &8(&7{object}&8)
            are no longer allied with them.'
      enemies:
        add:
          already: '&7{target} &7is already an enemy of {object}&7.'
          revoked: '&7You &8(&7{object}&8) revoked the neutralization offer for {target}&7.'
          nation: |
            &cYou can't declare land&4 {land} &cas an enemy. &7The land is governed by nation&9 {nation}&7.
              [T]&7✖ Declare nation&9 {nation} &7as an enemy instead: &e/{cmd} &8[CLICK][H]&7Click here to declare nation&9 {nation} &7as an enemy.[/H][C]{cmd}[/C][/T]
          success: '&7You &8(&7{object}&8) &7and {target} &7are now enemies.'
          broadcast: '&7{object} &7and {target} &7are now enemies.'
        remove:
          already: '&7{target} &7isn''t an enemy of&7 {object}&7.'
          success: '&7Successfully sent an neutralization offer to {target}&7. If
            they accept it, you &8(&7{object}&8) &7will no longer be enemies.'
    confirmtp:
      none: '&cYou have no active teleportation.'
    
    admin:
      listperms:
        header: '[NoPrefix][T]&7----------&e&l<<<<&7-[H]&7Click here to navigate to
          the previous page.[/H][C]{cmd} {player} {previous}[/C][/T] &2Perm List &7Page&3
          {page} &8/&3 {pages} [T]&7-&e&l>>>>&7----------[H]&7Click here to go to
          the next page.[/H][C]{cmd} {player} {next}[/C][/T]'
        footer: |
          [NoPrefix]
          &cPlayer &4{player} &chas these permissions, because they or their wildcard (perm.*) permissions are set in your permissions plugin. &7Click on the arrows below to navigate.

           &cRed = wildcard perms
           &eYellow = numbered perms
          [T]&7----------&e&l<<<<&7-[H]&7Click here to navigate to the previous page.[/H][C]{cmd} {player} {previous}[/C][/T] &2Perm List &7Page&3 {page} &8/&3 {pages} [T]&7-&e&l>>>>&7----------[H]&7Click here to go to the next page.[/H][C]{cmd} {player} {next}[/C][/T]
      land:
        addrole:
          confirm: |
            &cExecuting this command can lead to lands having the same role multiple times. &7For example newly created lands that already have this role inherited from roles.yml. Also executing this command for the same role multiple times will lead to role duplicates in affected lands. &7Please confirm this action:
              [T]&2✔ Confirm: &e/{fullcmd} &8[CLICK][H]&7Click here to confirm this action.[/H][C]{fullcmd}[/C][/T]
wars:
  message:
    noaccess:
      wilderness: '&cYou''re not allowed to do this in the wilderness while being
        engaged in a war. &8Flag: {flag}'
      general: '&cYou''re not allowed to do this in your current war against land&4
        {land}&c. &8Flag: {flag}'
      pillage: '&cYou can''t pillage the land&4 {land} &cwhile not enough defenders
        are online. &7Please wait until a minimum of&3 {defenders} &7defender(s) of
        land&2 {land} &7are online.'
    start:
      broadcast: '&7The war between {attacker} &7and {defender} &7started. It will
        be over in&5 {time}&7.'
    end:
      broadcast: '&7The war between {attacker} &7and {defender} &7ended. It took&5
        {time}&7.'
      surrender: '{object} &7surrendered. The war ended and they paid&c {tribute}
        &7to their enemy {enemy}&7.'
      draw: '&7The war between {attacker} &7and {defender} &7ended in a draw. It took&5
        {time}&7.'
    kill:
      target:
        attackers: '&7Our team mate&a {attacker} &7got killed by the defender&c {defender}&7.'
        defenders: '&7Our team mate&a {defender} &7got killed by the attacker&c {attacker}&7.'
      killer:
        attackers: '&7Our team mate&a {attacker} &7killed the defender&c {defender}&7:
          &a+ {points} points'
        defenders: '&7Our team mate&a {defender} &7killed the attacker&c {attacker}&7:
          &a+ {points} points'
    capture:
      place:
        wilderness: '&cYou can''t place a capture flag in the wilderness. &7You need
          to place it inside a enemy land.'
        overlap: '&cCapture blocks must be placed in a way that the beacon wouldn''t
          overlap with the wilderness.'
        region: '&cCan''t place capture flag here. &7It overlaps with a capture region
          of another capture flag.'
        outskirts: '&cCan''t place capture flag here. &7You must place it in the outskirts
          of the land.'
        state: '&cYou''re currently not at war against land&4 {land} &cor the war
          hasn''t started yet.'
        y: '&cCan''t place capture flag here. &7It must be placed between&3 {min}
          &7and&3 {max} &7blocks of height.'
        already: '&cCan''t place capture flag here. &7There''s already a capture flag
          placed in this chunk.'
        space: '&cCan''t place capture flag here. &7There''s not enough space at this
          position.'
        cooldown: '&cYou need to wait&4 {time} &cbefore your team can place a capture
          flag again.'
        max: '&cYour team already placed the maximum amount of&4 {max} &csimultaneously
          capture flags.'
        invader: '#t#&aCapture Point[newline]&aplaced in enemy land: {land}, {x},
          {y}, {z}[newline]&aJoin them to capture the area.'
        defender: '#t#&cCapture Point[newline]&cplaced in our land: {land}, {x}, {y},
          {z}[newline]&cGo there to join the defenders.'
      destroy:
        presense: '&cYou currently can''t break this capture flag. &7There are still&3
          {players} &7enemy players in this area.'
        invader: '#t#&cCapture Point[newline]&cin enemy land {land} has been destroyed'
        defender: '#t#&aCapture Point[newline]&aremoved from our land {land}[newline]&2&l+
          {points} points'
      none: '#b#[config]color:yellow,style:solid[/config]&7Capturing will start again,
        once there are more invaders than defenders.'
      progress:
        invaders:
          broadcast: '#b#[config]color:red,style:solid[/config]&cEnemy is capturing
            a part of {land} - {progress}%, {invaders} invader(s), x: {x}, y: {y},
            z: {z}'
          invaders: '#b#[config]style:solid[/config]&cWe are capturing - {progress}%,
            {defenders} defender(s)'
          defenders: '#b#[config]style:solid[/config]&cEnemy is capturing - {progress}%,
            {invaders} invader(s)'
        defenders:
          broadcast: '#b#[config]color:red,style:solid[/config]&aWe are capturing
            back a part of {land} - {progress}%, {invaders} invader(s), x: {x}, y:
            {y}, z: {z}'
          invaders: '#b#[config]style:solid[/config]&cDefenders are capturing back
            - {progress}%, {defenders} defender(s)'
          defenders: '#b#[config]style:solid[/config]&aWe are capturing back - {progress}%,
            {invaders} invader(s)'
      online: '#a#&cCan''t capture: Min. of {min} player(s) of land {land} need to
        be online.'
      success:
        invader: '#t#&aCapture Point[newline]&awe captured {chunks} chunk(s) from
          {land}[newline]&2&l+ {points} points'
        defender: '#t#&cCapture Point[newline]&cenemy captured {chunks} chunk(s) of
          {land}'
  command:
    general:
      no-war: '&cThere aren''t any upcoming or active wars for {object}&c. &7Everything
        is peaceful.'
    declare:
      confirm: |
        &7Please confirm that you &8(&7{attacker}&8) &7want to declare war against {defender}&7:
          [T]&2✔ Confirm: &e/{fullcmd} &8[CLICK][H]&7Click here to confirm this action.[/H][C]{fullcmd}[/C][/T]
      not-allowed: '&cYou''re not allowed to start a war for {object}&c. &7The leader
        of {object} &7needs to do this.'
      member: '&cYou can''t declare war against {object}&c. &7You or the enemy leader
        are trusted in common lands and / or a nation.'
      hour-of-day: '&cYou can only declare war between&4 {from} &ctill&4 {to}&c. &7Current
        time:&5 {current}&8 (&7time zone: {timezone}&8)'
      enemies: |
        &cYou must add&4 {object} &cas an enemy first.
          [T]&7✖ Add as Enemy: &e/{cmd} &8[CLICK][H]&7Click here to add {object} &7as an enemy in order to declare war on them.[/H][C]{cmd}[/C][/T]
      ally: |
        &cYou can''t declare war against your ally {object}&c.
          [T]&7✖ Manage Relations: &e/{cmd} &8[CLICK][H]&7Click here to manage your relations.[/H][C]{cmd}[/C][/T]
      war-shield: '&cYou currently can''t declare war against {object}&c. &7They have
        a war shield for the next&5 {time}&7.'
      no-nation: '&cYou can''t attack land&4 {land}&c. &7They must be part of a nation
        to be engaged in a war.'
      admin: '&cYou can''t declare war against admin lands.'
      nation: '&cYou can''t declare war against {object}&c. &7They''re part of the
        same nation&9 {nation}&7.'
      min-balance:
        attacker: '&cCan''t send this declaration. &7The attackers {object} &7need
          a minimum balance of&c {min} &7in order to start a war. Deposit money into
          your land bank: [T]&e/{cmd} &8[CLICK][H]&7Click here to deposit {min} into
          your land bank.[/H][C]{cmd}[/C][/T]'
        defender: '&cThe balance of the defenders {object} &cis too low. &7You can
          only attack others that have a minimum balance of&c {min}&7.'
      min-chunks:
        attacker: '&cCan''t send this declaration. &7The attackers {object} &7need
          a minimum amount of&c {min} &7chunks in order to start a war. Claim: [T]{cmd}
          &8[CLICK][H]&7Click here to claim.[/H][C]{cmd}[/C][/T]'
        defender: '&cThe claim amount of the defenders {object} &cis too low. &7You
          can only attack others that have a minimum amount of&c {min} &7chunks.'
      min-age:
        attacker: '&cCan''t send this declaration. &7The attackers {object} &7need
          to be at least&5 {min} &7old in order to start a war.'
        defender: '&cThe age of the defenders {object} &cis too low. &7You can only
          attack others that are at least&5 {min} &7old.'
      online: '&cCan''t send this declaration. &7At least one player of {object} &7need
        to be online.'
      broadcast: '&7The enemy {attacker} &7declared war against {defender}&7. Their
        war will start in&5 {time}&7.'
      success:
        normal: '&7You &8({object}&8) &7successfully declared war against {enemy}&7.
          The war will start in&5 {time}&7.'
        mutual:
          accepted: '&7You &8({object}&8) &7accepted the war against {enemy}&7. The
            war will start in&5 {time}&7.'
          sent: '&7You &8({object}&8) &7sent a war request to {enemy}&7. They need
            to accept it, before this war can start.'
      target: '&7The enemy {attacker} &7declared war against {defender} &8(&7YOU&8)&7.
        The war will start in&5 {time}&7.'
      mutual:
        success: '&7You &8({attacker}&8) &7successfully sent a war declaration to
          {defender}&7. &7They now need to accept or deny it, before the war can start.
          &7If the defenders surrender during war, they will need to pay&c {tribute}
          &7to the attackers.'
        target: |
          &7The enemy {attacker} &7send a war declaration against {defender} &8(&7YOU&8)&7. &7If the defenders surrender during war, they will need to pay&c {tribute} &7to the attackers.
           [T]&2✔ Accept &8[&8CLICK&8][H]&7Click here to accept the war declaration.[/H][C]wars declare {input}[/C][/T]
           [T]&c✘ Deny &8[&8CLICK&8][H]&7Click here to deny the war declaration.[/H][C]wars deny[/C][/T]
      already:
        attacker: '&cCan''t join another war. &7The current war of {object} &7needs
          to end first.'
        defender: '&cYou currently can''t declare war against them. &7The target {object}
          &7is already engaged in a war.'
      min-players:
        attacker: '&cYou can''t engage in a war, because {object} &cneeds more trusted
          players. &7The required minimum for attackers to declare war is&3 {min}
          &7players.'
        defender: '&cYou can''t declare war against {object}&c, because they need
          more trusted players. &7The required minimum for defenders to receive a
          war declaration is&3 {min} &7players.'
    deny:
      attacker: '&cAttackers can''t deny their own war declaration. &7Only the defender
        can do that.'
      ongoing: '&cYou can''t deny the ongoing war against {enemy}&c. &7You can only
        deny war declarations for {object}&7.'
      success: '&7You successfully denied the war declaration for {object} &7against
        the enemy {enemy}&7.'
    menu:
      mutual: '&cYou can''t open the war menu right now. &7The war declaration to
        {object} &7hasn''t been accepted yet.'
    spawn:
      none: '&cThe enemy {enemy} &chas no claims to teleport to.'
      success: '&7You were teleported near the border of enemy {enemy}&7.'
    info:
      war: |
        &4Current War:
        &8- &7Attacker {attacker}&7:
             &8• &7Captures: {att_cap}
             &8• &7Kills: {att_kills}
               &3= {att_points} / {towin} &7points to win
               {att_bar}
        &8- &7Defender {defender}&7:
             &8• &7Captures: {def_cap}
             &8• &7Kills: {def_kills}
               &3= {def_points} / {towin} &7points to win
               {def_bar}

        &7Timeout:&5 ~{time}
        [T]&7More info: &e/{cmd} &8[CLICK][H]&7Click here to open the war menu.[/H][C]{cmd}[/C][/T]
      declaration:
        normal: |
          &4War Declaration:
            &8• &7Attacker: {attacker}
            &8• &7Defender: {defender}
            &8• &7Starts in:
              &5~{time}

          [T]&7More info: &e/{cmd} &8[CLICK][H]&7Click here to open the war menu.[/H][C]{cmd}[/C][/T]
        mutual:
          defender: |
            &4War Declaration:
              &8• &7Attacker: {attacker}
              &8• &7Defender: {defender}
              &8• &7If you surrender during war:
                &7Tribute:&c {tribute}

            [T]&2✔ Accept: &e/{cmd_accept} &8[&8CLICK&8][H]&7Click here to accept the war declaration.[/H][C]{cmd_accept}[/C][/T]
            [T]&c✘ Deny: &e/{cmd_deny} &8[&8CLICK&8][H]&7Click here to deny the war declaration.[/H][C]{cmd_deny}[/C][/T]
          attacker: |
            &4War Declaration:
              &8• &7Attacker: {attacker}
              &8• &7Defender: {defender}f
              &8• &7If the defenders surrender:
                &7Tribute:&c {tribute}

            &cThe defender hasn't accepted
            &cthe declaration yet.
nations:
  message:
    current-war: '&cYou can''t do this right now. &7Your nation&9 {nation} &7is currently
      engaged in a war. &7Please try again after the war is over.'
    untrusted: '&cYou''re not a member of nation&4 {nation}&c.'
  command:
    chat:
      activated: '&7Activated nation chat. Send a message in public chat to chat with
        your nation.'
      deactivated: '&7Successfully deactivated nation chat.'
      none: "&cNo nation found for nation chat. \n  [T]&7✖ &7Disable chat mode: &e/{cmd}\
        \ &8[&8CLICK&8][H]&7Click here to deactivate the chat mode.[/H][C]{cmd}[/C][/T]\n"
      format:
        minecraft: '[NoPrefix]&9Nation {nation} &8| &7{player} &8»&f {message}'
        discord: '[NoPrefix]&9Nation {nation} &8| &9Discord &7{player} &8»&f {message}'
        spy: '[NoPrefix]&8[&cChatSpy&8] &9Nation {nation} &8| &7{player} &8»&f {message}'
    general:
      not-exist: '&cThe nation&9 {nation} &cdoesn''t exist. &7There''s no nation with
        this name.'
      no-member: '&cYou''re not a member of this nation&c. &7None of your lands is
        part of the nation&9 {nation}&7.'
      none: |
        &cYour land&4 {land} &cisn't part of any nation.

          &7Any nation can invite your land: &e/nations trust
          [T]&7Create your own nation: &e/{cmd} &8[CLICK][H]&7Click to copy.[/H][SC]{cmd}[/SC][/T]
      noaccess: '&cYou''re not allowed to do this for nation&4 {nation}&c. &8Flag:
        {flag}'
      not-trusted: '&cThe land&4 {land} &cisn''t a member of your nation&4 {nation}&c.'
    create:
      camp: |
        &cYou can't create a nation with a camp &8(&4{land}&8) &cas the capital.
          [T]&7✖ Create land: &e/{cmd_create} &8[CLICK][SC]{cmd_create}[/SC][H]&7Create a land. Click to copy.[/H][/T]
          [T]&7✖ Change edit land: &3/{cmd_edit} &8[CLICK][SC]{cmd_edit}[/SC][H]&7Use this command to change the edit land, which you want to be the capital of your nation. Click to copy.[/H][/T]
      already: '&cYour land&4 {land} &cis already part of the nation&4 {nation}&c.
        &7Your land needs to leave it first by executing &e/nations leave&7.'
      war: '&cYou can''t create a nation with land&4 {land} &cas the capital while
        it is engaged in a war against&4 {object}&c. &7Please try again after the
        war is over.'
      level: '&cYou currently can''t create a nation. &7Your land&2 {land} &7needs
        to be at least level&3 {level} &8(&7current: {current}&8)&7.'
      success: '&7You successfully created the nation&9 {nation} &7with the land&2
        {land} &7as the capital. [T]&7Click here to open the menu.[H]&7Open the menu.[/H][C]nations
        menu[/C][/T]'
    trust:
      camp: '&cCamps can''t be part of nations. &7The land&2 {land} &7is a camp.'
      max-distance: '&cThe land&4 {land} &cis too far away from the capital of nation&4
        {nation}&c. &7Max:&3 {max} block(s)&7, actual distance:&3 {distance} block(s)&7'
      already: '&cThe land&4 {land} &cis already part of the nation&4 {nation}&c.
        &7They need to leave it first by using &e/nations leave&7.'
      added: '&7You successfully added your land&2 {land} &7as a member of your nation&9
        {nation}&7.'
      success: '&7You successfully invited land&2 {land} &7to join your nation&9 {nation}&7.'
      target: |
        &7Nation&9 {nation} &7invited your land&2 {land} &7to join them.
          [T]&2✔ Accept: &e/{cmd_accept} &8[&8CLICK&8][H]&7Click here to accept this invite.[/H][C]{cmd_accept}[/C][/T]
          [T]&c✘ Deny: &e/{cmd_deny} &8[&8CLICK&8][H]&7Click here to deny this invite.[/H][C]{cmd_deny}[/C][/T]
    accept:
      war: '&cYou can''t join this nation right now. &7Nation&9 {nation} &7is currently
        engaged in a war against {object}&7. Please try again once their war is over.'
      none: '&cYour land&4 {land} &cdidn''t receive any invite from nation&9 {nation}&c.
        &7They can invite your land by executing &e/nations trust&7.'
      already: '&cYour land&4 {land} &cis already part of nation&4 {nation}&c. &7You
        need to leave it first by executing &e/nations leave&7.'
      success: '&7Your land&2 {land} &7is now part of nation&9 {nation}&7.'
    deny:
      success: '&7You successfully denied the invite from nation&9 {nation}&7.'
    untrust:
      capital: '&cYou can''t remove this land. &7Land&2 {land} &7is the capital of
        nation&9 {nation}&7.'
      already: '&cLand&4 {land} &cisn''t trusted in nation&4 {nation}&c.'
      success: '&7You successfully removed land&2 {land} &7from nation&9 {nation}&7.'
    delete:
      confirm: |
        &7Please confirm the deletion of nation&9 {nation} &7by clicking below:
          [T]&2✔ Confirm: &e/{fullcmd} &8[CLICK][H]&7Click here to confirm this action.[/H][C]{fullcmd}[/C][/T]
      war: '&cYou currently can''t delete your nation. &7Nation&9 {nation} &7is currently
        engaged in a war against {object}&7. Please try again when the war is over.'
      success: '&7Successfully deleted this nation &8(&7Nation:&2 {nation}&8)&7.'
    leave:
      confirm: |
        &7Please confirm that you want to remove land&2 {land} &7from nation&9 {nation}&7:
          [T]&2✔ Confirm: &e/{fullcmd} &8[CLICK][H]&7Click here to confirm this action.[/H][C]{fullcmd}[/C][/T]
      capital: '&cYour land&4 {land} &ccan''t leave nation&4 {nation}&c, because the
        land is the capital of this nation. &7To delete your nation, execute &e/nations
        delete&7.'
      war: '&cYou can''t leave this nation right now. &7Nation&9 {nation} &7is currently
        engaged in a war against {object}&7. Your war will be over in&5 {time}&7.'
      success: '&7You successfully left nation&9 {nation} &7with land&2 {land}&7.'
    rename:
      success: '&7Successfully set the new name&3 {name} &7for this nation &8(&7Nation:&9
        {nation}&8)&7. You paid&c {cost}&7.'
    setcapital:
      confirm: |
        &7Please confirm that you want to set land&2 {land} &7as the new capital of nation&9 {nation}&7:
          [T]&2✔ Confirm: &e/{fullcmd} &8[CLICK][H]&7Click here to confirm this action.[/H][C]{fullcmd}[/C][/T]
      level: '&cYou can''t set the land&4 {land} &cas the new capital of nation&4
        {nation}&c. &7It needs to be at least level&3 {level} &8(&7current: {current}&8)&7.'
      success: '&7Successfully set the land&2 {land} &7as the new capital of nation&9
        {nation}&7.'

list:
  swear-words: []
  hologram:
    landblock:
      main:
      - '&7Land&2 {land}'
      - '&7Inbox:&r {inbox}'
      - '&7Chunks: {chunks} / {chunks_max}'
      - '&7Members: {members} / {members_max}'
      - '&7Balance: {balance}'
      - '&7Upkeep and taxes in: {upkeep_next}'
    rent:
    - '&6Rent {area}'
    - '&c{cost} &7each &5{time}'
    - '&7Max duration: {max}'
    - '&8Click to rent.'
    sell:
      area:
      - '&aBuy'
      - '&7Area: &6{area}'
      - '&c{cost} &7in total'
      - '&8Click to purchase.'
      land:
      - '&aBuy'
      - '&7Land: &2{land}'
      - '&c{cost} &7in total'
      - '&8Click to purchase.'
    rented:
    - '&7Area&6 {area}'
    - '&7Tenant: {player}'
    - '&5{time} &7left'
    - '&c{cost} &7each &5{time}'
    - '&8Shift + click: Cancel'
    - '&8Click: Add more time'
    sold:
      area:
      - '&aSold'
      - '&7Area: &6{area}'
      - '&7To: {player}'
      - '&8Shift + click: Cancel'
      land:
      - '&aSold'
      - '&7Land: &2{land}'
      - '&7To: {player}'
  sign:
    top:
      entry:
      - '&6&l#{pos} {object}'
      - '&7of {owner}'
      - '&7{sorting}:'
      - '&3{value}'
      none:
      - ''
      - '&cNone'
      - ''
      - ''
    rent:
    - '&6&lRent {area}'
    - '&c{cost} &7/'
    - '&5{time}'
    - '&8Max: {max}'
    sell:
      area:
      - '&a&lBuy {area}'
      - '&7Blocks: {blocks}'
      - '&7Cost: &c{cost}'
      - '&8Click to buy.'
      land:
      - '&a&lBuy land'
      - '&2&l{land}'
      - '&7Cost: &c{cost}'
      - '&8Click to buy.'
    rented:
    - '&6&lRented'
    - '&7Area: &6{area}'
    - '&7To: {player}'
    - '&5{time} &7left'
    sold:
      area:
      - '&7&lSold'
      - '&7Area: &6{area}'
      - '&7To: {player}'
      land:
      - '&7&lSold'
      - '&7Land: &2{land}'
      - '&7To: {player}'
