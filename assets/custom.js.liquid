window.onload = initialInventory;

/**
 * Set default inventory by geo
 */
function initialInventory() {

	const setInventory = {
		// IT160
		Asia: () => {
			$('input[value="Asia"]').trigger("click");
			$('input[value="亞洲"]').trigger("click");
			$('input[value="亚洲"]').trigger("click");
			$('input[value="아시아"]').trigger("click");
			console.log('%c Inventory: Asia ', 'background: #5e8e3e; color: #fff');
		},
		// IT170
		Europe: () => {
			$('input[value="Europe"]').trigger("click");
			$('input[value="Europa"]').trigger("click");
			$('input[value="歐洲"]').trigger("click");
			$('input[value="欧洲"]').trigger("click");
			$('input[value="유럽"]').trigger("click");
			console.log('%c Inventory: Europe ', 'background: #5e8e3e; color: #fff');
		}
	}

	fetch('https://api.ipstack.com/check?access_key=1064c5485963a2fe844a3d485b1b339a')
		.then(res => res.json())
		.then(res => {
			console.log(`%c Ipstack: ${res.continent_code} ${res.country_code} `, 'background: #379f79; color: #fff');
			switch (res.continent_code) {
				case 'AS':
					// Special case
					['JP'].includes(res.country_code)
						? setInventory.Europe()
						: setInventory.Asia();
					break;
				case 'EU':
				case 'NA':
				case 'SA':
				default:
					setInventory.Europe();
					break;
			}
		})
		.catch(error => {
			console.error('ipstack', error);
		})
}