<div>
   <h1 id="title">DigiTheo Ground Truth</h1>
   <p id="paragraph">This repository contains transcriptions for some journals which were digitized by the University Library of Tübingen in the DigiTheo project (http://idb.ub.uni-tuebingen.de/digitue/theo/).</p>
   <h2>Metadata</h2>
   <dl class="grid">
      <dt id="Language">Language:</dt>
      <dd>deu</dd>
      <dt id="Format">Format:</dt>
      <dd>Page-XML</dd>
      <dt id="Time">Time:</dt>
      <dd>1860-1872</dd>
      <dt id="GTT">GT Type:</dt>
      <dd>data_line</dd>
      <dt id="License">License:</dt>
      <dd>CC0 1.0</dd>
      <dt id="Guidelines">Transcription Guidelines:</dt>
      <dd>The transcriptions were done with eScriptorium, a transcription platform developed as part of the Scripta and RESILIENCE projects (https://gitlab.com/scripta/escriptorium/).</dd>
      <dt id="Project">Project:</dt>
      <dd>Theologie digital</dd>
      <dt id="Project-URL">Project-URL:</dt>
      <dd>http://idb.ub.uni-tuebingen.de/digitue/theo/</dd>
   </dl>
   <h2>Sources</h2>
   <h3>The volume of transcriptions:</h3>
   <table id="table_id">
      <thead>
         <tr>
            <th>TextLine</th>
            <th>Page</th>
            <th>TxtRegion</th>
         </tr>
      </thead>
      <tbody>
         <tr>
            <td>6182</td>
            <td>163</td>
            <td>443</td>
         </tr>
      </tbody>
   </table>
   <div id="transcriptions">
      <h3>List of transcriptions</h3>
      <div>
         <table class="noStyle"/>
         <table id="table_id" class="display">
            <thead>
               <tr>
                  <th>document</th>
                  <th>TxtRegion</th>
                  <th>TextLine</th>
                  <th>Page</th>
               </tr>
            </thead>
            <tbody>
               <tr>
                  <td>Stimmen_aus_Maria-Laach/1871</td>
                  <td>73</td>
                  <td>945</td>
                  <td>25</td>
               </tr>
               <tr>
                  <td>Stimmen_aus_Maria-Laach/1872</td>
                  <td>244</td>
                  <td>3340</td>
                  <td>88</td>
               </tr>
               <tr>
                  <td>Allgemeine_kirchliche_Zeitschrift/1860</td>
                  <td>87</td>
                  <td>1166</td>
                  <td>30</td>
               </tr>
               <tr>
                  <td>Die_paepstliche_Unfehlbarkeit</td>
                  <td>39</td>
                  <td>731</td>
                  <td>20</td>
               </tr>
            </tbody>
         </table>
      </div>
   </div>
   <div id="extent">
      <h2>Extent</h2>
      <p>After exporting the transcriptions as PAGE XML files, those files were
         processed to remove empty lines:</p>

      perl -i -ne "tr|\r||d; next if /^\s*$/;print" *.xml

      
   </div>
</div>
