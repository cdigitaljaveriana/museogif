{% assign imagesample = site.data[site.metadata] | where_exp: 'item','item.format contains "image"' | first %} {% capture imagesampleid %}{{imagesample.objectid | default: "https://www.lib.uidaho.edu/collectionbuilder/demo-objects/mg101_b6_photographs_01.jpg"}}{% endcapture %} {% assign pdfsample = site.data[site.metadata] | where_exp: 'item','item.format contains "pdf"' | first %} {% capture pdfsampleid %}{{pdfsample.objectid | default: "https://www.lib.uidaho.edu/collectionbuilder/demo-objects/uiext21768.pdf"}}{% endcapture %} {% assign videosample = site.data[site.metadata] | where_exp: 'item','item.format contains "video"' | first %} {% capture videosampleid %}{{videosample.objectid | default: "https://cdil.lib.uidaho.edu/storying-extinction/objects/trailcams/videos/ballcreek-cedarrub-birdonpath.mp4"}}{% endcapture %} {% assign audiosample = site.data[site.metadata] | where_exp: 'item','item.format contains "audio"' | first %} {% capture audiosampleid %}{{audiosample.objectid | default: "https://www.lib.uidaho.edu/digital/mp3s/Clouds.mp3"}}{% endcapture %}

## Créditos

<div class="container-fluid mt-4 mb-n3 bg-light p-4 " id="technical">
    <div class="container mt-4 border rounded p-4 bg-white">
        <h3>Technical Credits - CollectionBuilder</h3>
        <div class="row my-2 justify-content-center">
            <div class="col-md-8 p-4">
                <p>This digital collection is built with <a href="https://collectionbuilder.github.io/" target="_blank" rel="noopener">CollectionBuilder</a>, an open source framework for creating digital collection and exhibit websites that is developed by faculty librarians at the University of Idaho Library following the <a href="https://lib-static.github.io" target="_blank" rel="noopener">Lib-Static</a> methodology.</p>
                <p>The site started from the <a href="https://github.com/CollectionBuilder/collectionbuilder-gh" target="_blank" rel="noopener">CollectionBuilder-GH</a> template which utilizes the static website generator <a href="https://jekyllrb.com/" target="_blank" rel="noopener">Jekyll</a> and <a href="https://pages.github.com/" target="_blank" rel="noopener">GitHub Pages</a> to build and host digital collections and exhibits.</p>
            </div>
        </div>
    </div>
</div>


 <div class="container mt-4 border rounded p-4 bg-white">
        <h3>Technical Credits - CollectionBuilder</h3>
        <div class="row my-2 justify-content-center">
            <div class="col-md-8 p-4">
                <p>This digital collection is built with <a href="https://collectionbuilder.github.io/" target="_blank" rel="noopener">CollectionBuilder</a>, an open source framework for creating digital collection and exhibit websites that is developed by faculty librarians at the University of Idaho Library following the <a href="https://lib-static.github.io" target="_blank" rel="noopener">Lib-Static</a> methodology.</p>
                <p>The site started from the <a href="https://github.com/CollectionBuilder/collectionbuilder-gh" target="_blank" rel="noopener">CollectionBuilder-GH</a> template which utilizes the static website generator <a href="https://jekyllrb.com/" target="_blank" rel="noopener">Jekyll</a> and <a href="https://pages.github.com/" target="_blank" rel="noopener">GitHub Pages</a> to build and host digital collections and exhibits.</p>
            </div>
            <div class="col-md-4 text-center">
                <h4>More Information Available</h4>
                <a class="btn btn-outline-primary my-2" target="_blank" rel="noopener" href="https://collectionbuilder.github.io/about.html">Technical Specifications</a>
                <br>
                <a class="btn btn-outline-secondary my-2" target="_blank" rel="noopener" href="https://collectionbuilder.github.io/about.html#support">IMLS Support</a>
            </div>
        </div>
    </div>






    
</div>



## Galería
