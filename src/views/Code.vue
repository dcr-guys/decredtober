<template>
  <div>
    <section>
      <div class="hero is-medium is-info is-bold">
        <div class="hero-body">
          <div class="container">
            <h1 class="title">
              Code
            </h1>
            <h2 class="subtitle">
              Hacktoberfest.
            </h2>
          </div>
        </div>
      </div>
      <div class="container content content-space">
        <h2 class="title is-2" id="event-details">
          <a href="#event-details">Event details</a>
        </h2>
        <p>
          Hacktoberfest is open to everyone in our global community. Whether you’re a
          developer, student learning to code, event host, or company of any size, you can help drive growth of open
          source and make positive contributions to an ever-growing community. All backgrounds and skill levels are
          encouraged to complete the challenge.
        </p>
        <ul>
          <li>
            <span>Hacktoberfest is a celebration <strong>open to everyone</strong> in our global community.</span>
          </li>
          <li>
            <span>Pull requests can be made in <strong>any GitHub-hosted repositories/projects.</strong></span>
          </li>
          <li>
            <span>You can sign up anytime between October 1 and October 31.</span>
          </li>
        </ul>

        <h2 class="title is-2" id="rules">
          <a href="#rules">Rules</a>
        </h2>
        <p>
          To earn your Hacktoberfest tee or tree reward, you must register and make four valid pull requests (PRs) between
          October 1-31 (in any time zone). PRs can be made to any public repo on GitHub, not only the ones with issues
          labeled Hacktoberfest. If a maintainer reports your pull request as spam or behavior not in line with the
          project’s code of conduct, you will be ineligible to participate. This year, the first 70,000 participants who
          successfully complete the challenge will be eligible to receive a prize.
        </p>
        <p>Read the <a href="/details">participation details</a> to learn how to
          earn your Hacktoberfest tee or tree reward.</p>
      </div>
    </section>
    <section>
      <div class="container column">
        <div class="tile is-ancestor">
          <div class="tile is-vertical is-8">
            <div class="tile">
              <div class="tile is-parent is-vertical">
                <article class="tile content is-child notification is-primary">
                  <p class="title">Step 1</p>
                  <hr>
                  <p class="subtitle">
                    Join the communty channels:
                  </p>
                  <ul>
                    <li><a href="https://chat.decred.org/">Matrix (Main chat)</a></li>
                    <li><a href="https://t.me/decred">Telegram</a></li>
                    <li><a href="https://discord.gg/GJ2GXfz">Discord</a></li>
                    <li><a href="https://decred.org/community/">Others</a></li>
                  </ul>
                </article>
                <article class="tile is-child notification is-warning">
                  <p class="title">Step 2</p>
                  <hr>
                  <p class="subtitle">
                    Grab an issue to work on it! Look at the sugested list.
                  </p>
                </article>
              </div>
              <div class="tile is-parent">
                <article class="tile is-child notification is-info">
                  <p class="title">Helper sessions</p>
                  <hr>
                  <p class="subtitle">
                    Blockchain and cryptocurrencies is not a simple world, but you can keep eyes in or help sessions to understand how projects works, how to run develepmen envroment.
                  </p>
                  <ul>
                    <li><a href="#">01/10 - 18h00 UTC-3 Conhecendo o projeto Decred</a></li>
                    <li><a href="#">08/10 - 18h00 UTC-3 Ambiente dev blockchain</a></li>
                    <li><a href="#">15/10 - 18h00 UTC-3 Ambiente dev blockchain</a></li>
                    <li><a href="#">22/10 - 18h00 UTC-3 Ambiente dev blockchain</a></li>
                  </ul>
                </article>
              </div>
            </div>
          </div>
          <div class="tile is-parent">
            <article class="tile is-child notification is-dark">
              <div class="content">
                <p class="title">Suggested repositories</p>
                <div class="content">
                  <p>Decred daemon in Go (golang).</p>
                  <b-button
                    icon-left="github"
                    href="https://github.com/decred/dcrd"
                    target="_blank"
                    >
                    dcrd
                  </b-button>
                  <hr>
                  <p>A secure Decred wallet daemon written in Go (golang).</p>
                  <b-button
                    icon-left="github"
                    href="https://github.com/decred/dcrwallet"
                    target="_blank"
                    >
                    dcrwallet
                  </b-button>
                  <hr>
                  <p>Decred Lightning Network Daemon (golang).</p>
                  <b-button
                    icon-left="github"
                    href="https://github.com/decred/dcrlnd"
                    target="_blank"
                    >
                    dcrlnd
                  </b-button>
                  <hr>
                  <p>Politeia is the Decred proposal system(golang).</p>
                  <b-button
                    icon-left="github"
                    href="https://github.com/decred/politeia"
                    target="_blank"
                    >
                    politeia
                  </b-button>
                  <hr>
                  <p>Politeia UI library (ReactJs).</p>
                  <b-button
                    icon-left="github"
                    href="https://github.com/decred/pi-ui"
                    target="_blank"
                    >
                    politeia
                  </b-button>
                  <hr>
                  <p>Cross-platform GUI for Decred (Electron).</p>
                  <b-button
                    icon-left="github"
                    href="https://github.com/decred/decrediton"
                    target="_blank"
                    >
                    politeia
                  </b-button>
                  <hr>
                  <p> Find more in <a href="https://github.com/decred">Decred Github's page</a></p>

                </div>
              </div>
            </article>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: 'Code'
}
</script>

<style scoped>
.content-space {
  padding-top: 50px;
}
</style>
