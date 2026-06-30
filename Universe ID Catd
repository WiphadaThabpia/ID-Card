import { StatusBar } from 'expo-status-bar';
import { StyleSheet, Text, View, Image} from 'react-native';

const App = () => {
  return (
    <View style={styles.container}>
      <Image source={{ uri: 'https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRU6O5mB-8DYAuKOyc_1lUOoyagMZmUox26ALdx0j84XHBzf_IcN1hYreIU&s=10'}}
      style={styles.image}
      />
      <StatusBar style="auto" />
      <Text style={styles.title}>Universe ID Card </Text>
      <Text style={styles.name}>Miss Wiphada Thabpia </Text>
      <Text style={styles.position}>Student</Text> 
    </View>
  );
}

const styles = StyleSheet.create({
  container: {
    flex: 1,
    backgroundColor: 'lightblue',
    alignItems: 'center',
    justifyContent: 'center',
    borderRadius: 40,
    borderWidth: 10,
    borderColor: '#5781f5'

  },
  title: {
    fontSize: 25,
    fontWeight: 'bold'
  },
  image: { width: 300, height: 300, marginTop: 10, borderRadius: 350,
    resizeMode: 'cover', borderWidth: 3, borderColor: '#1c73e6'
  },
  name: {
    fontSize: 20,
    fontWeight: 'bold',
    width: 250, height: 40, marginTop: 20, borderRadius: 10,
    resizeMode: 'cover', borderWidth: 3, borderColor: '#962196',backgroundColor: 'white'
  },
  position: {
    fontSize:20,
    fontWeight: 'bold',
    width: 250, height: 40, marginTop: 20, borderRadius: 10,
    resizeMode: 'cover', borderWidth: 3, borderColor: '#962196',backgroundColor: 'white'
  }
});

export default App
