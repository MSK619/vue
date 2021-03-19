
    <!-- <template> -->
        
        <div id="element"><p>{{first_msg}}</p></div>fdsfd
        
        <b>
            <router-link to='/second_page'>Got To SEcond page</router-link>
        </b>
    

    <!-- </template> -->

    <script src="lib/vue.js"></script>
    <!-- <script src="router.js"></script> -->
    <script>
        
    

        // var first_msg ='meesage';
        
        var vue_obj = new Vue({
            el:"#element",
            data:{
                first_msg:'mssage given here',
            },
           
            
        });
        // import second_page_link from './second_page.html';

    </script>

