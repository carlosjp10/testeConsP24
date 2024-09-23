<script src="https://unimedrp--dev.sandbox.my.salesforce-sites.com/formulariolightning/lightning.out.js"></script>

<div data-lightning-out="true"></div>

<script>
    const appName = 'c:consultarCasoApp';
    const componentName = 'c:consultarCasos';
    const lightningEndpoint = 'https://unimedrp.my.salesforce-sites.com/';
    const targetElement = document.querySelector("[data-lightning-out]");
    const componentAttributes = {

    };

    $Lightning.use(
        appName,
        function(){
            $Lightning.createComponent(
                componentName,
                componentAttributes,
                targetElement,
                function(cmp){
                    console.log('@cac funcionando');
                }
            );
        },
        lightningEndpoint
    );
</script>
