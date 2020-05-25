async componentDidMount() {
    try {
      const response = await fetch(`http://httpstat.us/500`);
      if (!response.ok) {
        throw Error(response.statusText);
      }
    } catch (error) {
      console.log(error);
    }
}
