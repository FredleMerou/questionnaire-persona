const questions = [
    {
        question: "Vous vous sentez plus énergisé(e) par un groupe de personnes que par un moment seul(e).",
        options: ["D'accord", "Pas d'accord"],
        dimension: "E-I"
    },
    {
        question: "Vous préférez planifier et organiser plutôt que d'improviser.",
        options: ["D'accord", "Pas d'accord"],
        dimension: "J-P"
    },
    {
        question: "Vous prenez des décisions plutôt basées sur la logique que sur les émotions.",
        options: ["D'accord", "Pas d'accord"],
        dimension: "T-F"
    },
    {
        question: "Vous vous fiez davantage aux faits concrets qu'aux idées abstraites.",
        options: ["D'accord", "Pas d'accord"],
        dimension: "S-N"
    }
];

const dimensionScores = {
    "E-I": 0,
    "J-P": 0,
    "T-F": 0,
    "S-N": 0
};

const questionnaire = document.getElementById("questionnaire");

questions.forEach((q, index) => {
    const questionDiv = document.createElement("div");
    questionDiv.className = "question";

    const questionLabel = document.createElement("label");
    questionLabel.innerText = q.question;
    questionDiv.appendChild(questionLabel);

    q.options.forEach(option => {
        const optionLabel = document.createElement("label");
        const optionInput = document.createElement("input");
        optionInput.type = "radio";
        optionInput.name = `question${index}`;
        optionInput.value = option;
        optionLabel.appendChild(optionInput);
        optionLabel.appendChild(document.createTextNode(option));
        questionDiv.appendChild(optionLabel);
    });

    questionnaire.appendChild(questionDiv);
});

document.getElementById("submitBtn").addEventListener("click", () => {
    questions.forEach((q, index) => {
        const selectedOption = document.querySelector(`input[name="question${index}"]:checked`);
        if (selectedOption) {
            const value = selectedOption.value;
            if (value === "D'accord") {
                dimensionScores[q.dimension]++;
            } else {
                dimensionScores[q.dimension]--;
            }
        }
    });

    const result = `
        ${dimensionScores["E-I"] > 0 ? "E" : "I"}
        ${dimensionScores["S-N"] > 0 ? "S" : "N"}
        ${dimensionScores["T-F"] > 0 ? "T" : "F"}
        ${dimensionScores["J-P"] > 0 ? "J" : "P"}
    `.replace(/\s/g, "");

    document.getElementById("result").innerText = `Votre type de personnalité est : ${result}`;
});
