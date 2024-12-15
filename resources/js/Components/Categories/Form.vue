<script>
    export default{
        name: 'CategoriesForm'
    }
</script>

<script setup>
import FormSection from '../FormSection.vue';
import InputError from '../InputError.vue';
import InputLabel from '../InputLabel.vue';
import PrimaryButton from '../PrimaryButton.vue';
import TextInput from '../TextInput.vue';

    defineProps({
        form:{
            type:Object,
            required:true
        },
        updating:{
            type:Boolean,
            required:false,
            default:false
        }
    })

    defineEmits(['submit'])
</script>
