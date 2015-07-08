<td id="wikicontent" class="psdescription">
 <h1><a name="A_Java_library_to_read_dwarf"></a>A Java library to read dwarf<a href="#A_Java_library_to_read_dwarf" class="section_anchor"></a></h1><p>It is a java version of libdwarf, if you want to read out information from dwarf. please use it. </p><p><font color="red">!!! Please always use the latest code from SVN, rather than download the jar</font> </p><p>Usage : </p><pre class="prettyprint"><span class="kwd">final</span><span class="pln"> </span><span class="typ">Vector</span><span class="pun">&lt;</span><span class="typ">Dwarf</span><span class="pun">&gt;</span><span class="pln"> dwarfVector </span><span class="pun">=</span><span class="pln"> </span><span class="typ">DwarfLib</span><span class="pun">.</span><span class="pln">init</span><span class="pun">(</span><span class="pln">file</span><span class="pun">,</span><span class="pln"> meoryOffset</span><span class="pun">);</span></pre><p>All dwarf information will be in dwarfVector </p><p>To add a JPanel to display dwarf information : </p><pre class="prettyprint"><span class="typ">PeterDwarfPanel</span><span class="pln"> peterDwarfPanel1 </span><span class="pun">=</span><span class="pln"> </span><span class="kwd">new</span><span class="pln"> </span><span class="typ">PeterDwarfPanel</span><span class="pun">();</span><span class="pln"><br></span><span class="typ">File</span><span class="pln"> file </span><span class="pun">=</span><span class="pln"> </span><span class="kwd">new</span><span class="pln"> </span><span class="typ">File</span><span class="pun">(</span><span class="str">"/Users/peter/workspace/PeterI/kernel/kernel"</span><span class="pun">);</span><span class="pln"><br>peterDwarfPanel1</span><span class="pun">.</span><span class="pln">init</span><span class="pun">(</span><span class="pln">file</span><span class="pun">.</span><span class="pln">getAbsolutePath</span><span class="pun">());</span></pre><p>Then just add peterDwarfPanel1 to any swing container. </p><p>contact : mcheung63@hotmail.com, my name is Peter </p><p>example: <a href="http://code.google.com/p/peter-dwarf/source/browse/trunk/src/com/peterdwarf/TestPeterDwarf.java" rel="nofollow">http://code.google.com/p/peter-dwarf/source/browse/trunk/src/com/peterdwarf/TestPeterDwarf.java</a> </p><p><a href="http://peter-dwarf.googlecode.com/files/a00024_a29e9ccd226cccc310768931f03571dd0_cgraph.png" rel="nofollow"><img src="http://peter-dwarf.googlecode.com/files/a00024_a29e9ccd226cccc310768931f03571dd0_cgraph.png"></a> </p><p><a href="http://www3.clustrmaps.com/user/41df3692" rel="nofollow"><img src="http://www3.clustrmaps.com/stats/maps-no_clusters/code.google.com-p-peter-dwarf--thumb.jpg" alt="Locations of visitors to this page"> </a> </p><p><img src="http://dwarfstd.org/dwarf_logo.gif"> </p><p><a href="http://dwarfstd.org/" rel="nofollow">Dwarf specification</a> </p>
 </td>
