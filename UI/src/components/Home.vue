<template>
<div>
  <div id="welcome" style="width:100%">
    <h1 style="margin-bottom: 3em">Welcome to LedgerSMB</h1>
    <div style="float:left; width:calc(33.3% - 1em); padding: 1em; margin: 0.5em; border: 1px solid black; border-radius: 0.5em; min-width: 300px; box-sizing: border-box">
      <h2>What is LedgerSMB</h2>
      <p>LedgerSMB is a double entry accounting system offering a wide
        variety of related functionalities, such as</p>
        <ul>
          <li>invoicing</li>
          <li>bank reconciliation</li>
          <li>ordering</li>
          <li>keeping stock</li>
          <li>tracking hours (timecards)</li>
          <li>shipping &amp; receiving</li>
          <li>tracking of unpaid invoices</li>
        </ul>
    </div>
    <div style="float:left; width:calc(33.4% - 1em); padding: 1em; margin: 0.5em; border: 1px solid black; border-radius: 0.5em; min-width: 300px; box-sizing: border-box">
      <h2>Community resources</h2>
      <p>Community support for LedgerSMB is a available through various
        channels, ranging from static all the way to near-realtime (depending
        on availability of people):</p>
      <ul>
        <li>The <a href="https://ledgersmb.org" target="_blank"
                   rel="noopener noreferrer">project
            website</a></li>
        <li>The <a href="https://ledgersmb.org/FAQ" target="_blank"
                   rel="noopener noreferrer">FAQ</a></li>
        <li>The <a href="http://archive.ledgersmb.org/" target="_blank"
                   rel="noopener noreferrer">mailing list
            archives</a></li>
      </ul>
      <p>For a more interactive experience, please join
        one of the <a href="http://lists.ledgersmb.org/" target="_blank"
                      rel="noopener noreferrer">mailing lists</a></p>

      <p>There's also the near-realtime chat experience in the
        <a href="https://app.element.io/%23/room/%23ledgersmb:matrix.org"
           target="_blank" rel="noopener noreferrer">matrix
            &quot;LedgerSMB&quot; room</a></p>
    </div>
    <div style="float:left; width:calc(33.3% - 1em); padding: 1em; margin: 0.5em; border: 1px solid black; border-radius: 0.5em; min-width: 300px; box-sizing: border-box">
      <h2>Contributing</h2>
      <p>The project is always looking for contributions. The easiest ways to
        contribute to the project are:</p>
      <ul>
        <li>Report your bugs and problems
          to <a href="https://github.com/ledgersmb/LedgerSMB/issues/">the
            project's GitHub bug tracker</a> or
          <a href="https://lists.ledgersmb.org/">mailing lists</a></li>
        <li>Help translate the software through the <a href="https://www.transifex.com/ledgersmb/ledgersmb/">LedgerSMB
            project Transifex web-based translation project</a></li>
        <li>Fix a <a href="https://github.com/ledgersmb/LedgerSMB/issues?q=is%3aopen%20is%3aissue%20label%3abite-sized%20-label%3aenhancement">bug</a> and
          submit a &quot;Pull Request&quot;<br />
          When you do, please start with one marked 'bite-sized' and contact
          the development team through IRC and/or matrix for help getting
          started.</li>
      </ul>
    </div>
  </div>
</div>
</template>

<script>

function markDone() {
    document.getElementById("maindiv").classList.add("done-parsing");
}

export default {
    mounted() {
        markDone();
    },
    updated() {
        markDone();
    }
};
</script>
