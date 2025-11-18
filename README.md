# add-function-reset-draft-21
function resetMyGarage() external override {
        delete garages[msg.sender];
    }
