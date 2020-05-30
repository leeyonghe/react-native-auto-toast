# react-native-auto-toast
- 선언 <br>
import Toast from 'react-native-auto-toast'; <br> <br>
- 사용 <br>
<View> <br>
<Toast ref="toast"/> <br>
</View> <br>
<TouchableOpacity onPress={() => {this.refs.toast.show('Confirm!');}}> <br>
    <Text>Confirm</Text> <br>
</TouchableOpacity> <br>
