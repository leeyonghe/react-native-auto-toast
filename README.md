# react-native-auto-toast
- 선언 <br>
import Toast from 'react-native-auto-toast'; <br> <br>
- 사용 <br>
<View>
<Toast ref="toast" backgroundColor="#000000" opacitys="0.5"/>
</View>
<TouchableOpacity onPress={() => {this.refs.toast.show('Confirm!');}}>
    <Text>Confirm</Text>
</TouchableOpacity>